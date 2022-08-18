<template>
<div id="map" style="width:100%;  height:700px;margin:0 auto; overflow:hidden; border:1px solid;"></div>
</template>

<script>
import axios  from "axios";
    axios.defaults.withCredentials = true;
  export default {
    name :"KakaoMap",
    data(){
      return{
        markerList : [],
        infowindowList : [],
        positions : []
      }
    },
    mounted(){
      if (window.kakako && window.kakako.maps) {
        this.initMap();
      } else{
        const script = document.createElement("script")
        script.onload = () => kakao.maps.load(this.initMap);
        script.src="//dapi.kakao.com/v2/maps/sdk.js?autoload=false&appkey=cfd4e527f6a472cb323f1ffa306cf3a8&libraries=services"
        document.head.appendChild(script)
      }
    },
    methods :{
      initMap(){
        var mapContainer = document.getElementById('map'), // 지도를 표시할 div
        mapOption = {
            center: new kakao.maps.LatLng(34.74756145157297, 127.74561623573636), // 지도의 중심좌표
            level: 5 // 지도의 확대 레벨
        };

	      this.map = new kakao.maps.Map(mapContainer, mapOption);
      },
      hotelService(){
        var getList =axios({
          method: 'post',
          url: 'http://localhost:3000/hotel',
          headers: {'X-Requested-With': 'XMLHttpRequest'} ,
          responseType: 'json'
        })
          .then((Response)=>{
            return Response.data;
          })
          .catch(function (error) {
            // 에러 핸들링
            console.log(error.toJSON());
          })
          return {getList:getList}
      }
    }
  }
</script>

<style>

</style>
