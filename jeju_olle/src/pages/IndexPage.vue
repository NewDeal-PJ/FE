<template>
  <div id="app">
    <Header></Header>
    <Home></Home>
    <HomeMap></HomeMap>
    <HomeBody></HomeBody>
    <Footer></Footer>

  </div>
</template>

<script>
import Home from '../components/Home/Home.vue';
import Header from '../components/Home/Header.vue';
import HomeMap from 'src/components/Home/HomeMap.vue';
import HomeBody from 'src/components/Home/HomeBody.vue';
import Footer from '../components/Home/Footer.vue';





export default {
  components: {
    Home,
    Header,
    HomeMap,
    HomeBody,
    Footer
}
}
// import { defineComponent } from 'vue'

// export default defineComponent({
//   name: 'IndexPage'
// })
</script>
