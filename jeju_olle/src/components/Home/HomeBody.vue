<template>

<!-- v-for -->
<div style="font-size: 30px; font-weight: bold; margin-left: 80px;"> 🏡 BEST HOTEL 10</div>
<main>
  <div class="q-pa-md">
    <q-carousel
      v-model="slide"
      transition-prev="slide-right"
      transition-next="slide-left"
      swipeable
      animated
      control-color="primary"
      navigation
      padding
      arrows
      >
      <q-carousel-slide :name="1" class="column no-wrap">
        <div class="row fit justify-start items-center q-gutter-xs q-col-gutter no-wrap">
          <q-card class="my-card">
            <q-img src="https://search.pstatic.net/common/?src=https://media.datahc.com/HI595096817.jpg&type=f1128_672_hotel" style="height: 150px;"/>

            <q-card-section>
              <q-btn
                fab
                color="primary"
                icon="place"
                class="absolute"
                style="top: 0; right: 12px; transform: translateY(-50%);" />

              <div class="row no-wrap items-center">
                <div class="col text-h6 ellipsis">
                  롯데 호텔 제주
                </div>
                <div class="col-auto text-grey text-caption q-pt-md row no-wrap items-center">
                  <q-icon name="place" />
                  서귀포
                </div>
              </div>

              <q-rating v-model="stars" :max="5" size="25px" />
            </q-card-section>

            <q-card-section class="q-pt-none">
              <div class="text-caption text-grey">
                "수영장이 매우 좋음"
              </div>
              <div class="text-subtitle1 text-red">
                117,187원~
              </div>
            </q-card-section>
            <q-separator />
            </q-card>
          <q-card class="my-card">
            <q-img src="https://search.pstatic.net/common/?src=https://media.datahc.com/HI595096817.jpg&type=f1128_672_hotel" style="height: 150px;"/>

            <q-card-section>
              <q-btn
                fab
                color="primary"
                icon="place"
                class="absolute"
                style="top: 0; right: 12px; transform: translateY(-50%);" />

              <div class="row no-wrap items-center">
                <div class="col text-h6 ellipsis">
                  롯데 호텔 제주
                </div>
                <div class="col-auto text-grey text-caption q-pt-md row no-wrap items-center">
                  <q-icon name="place" />
                  서귀포
                </div>
              </div>

              <q-rating v-model="stars" :max="5" size="25px" />
            </q-card-section>

            <q-card-section class="q-pt-none">
              <div class="text-caption text-grey">
                "수영장이 매우 좋음"
              </div>
              <div class="text-subtitle1 text-red">
                117,187원~
              </div>
            </q-card-section>
            <q-separator />
            </q-card>
          <q-card class="my-card">
            <q-img src="https://search.pstatic.net/common/?src=https://media.datahc.com/HI595096817.jpg&type=f1128_672_hotel" style="height: 150px;"/>

            <q-card-section>
              <q-btn
                fab
                color="primary"
                icon="place"
                class="absolute"
                style="top: 0; right: 12px; transform: translateY(-50%);" />

              <div class="row no-wrap items-center">
                <div class="col text-h6 ellipsis">
                  롯데 호텔 제주
                </div>
                <div class="col-auto text-grey text-caption q-pt-md row no-wrap items-center">
                  <q-icon name="place" />
                  서귀포
                </div>
              </div>

              <q-rating v-model="stars" :max="5" size="25px" />
            </q-card-section>

            <q-card-section class="q-pt-none">
              <div class="text-caption text-grey">
                "수영장이 매우 좋음"
              </div>
              <div class="text-subtitle1 text-red">
                117,187원~
              </div>
            </q-card-section>
            <q-separator />
            </q-card>
          <q-card class="my-card">
            <q-img src="https://search.pstatic.net/common/?src=https://media.datahc.com/HI595096817.jpg&type=f1128_672_hotel" style="height: 150px;"/>

            <q-card-section>
              <q-btn
                fab
                color="primary"
                icon="place"
                class="absolute"
                style="top: 0; right: 12px; transform: translateY(-50%);" />

              <div class="row no-wrap items-center">
                <div class="col text-h6 ellipsis">
                  롯데 호텔 제주
                </div>
                <div class="col-auto text-grey text-caption q-pt-md row no-wrap items-center">
                  <q-icon name="place" />
                  서귀포
                </div>
              </div>

              <q-rating v-model="stars" :max="5" size="25px" />
            </q-card-section>

            <q-card-section class="q-pt-none">
              <div class="text-caption text-grey">
                "수영장이 매우 좋음"
              </div>
              <div class="text-subtitle1 text-red">
                117,187원~
              </div>
            </q-card-section>
            <q-separator />
            </q-card>
          <q-card class="my-card">
            <q-img src="https://search.pstatic.net/common/?src=https://media.datahc.com/HI595096817.jpg&type=f1128_672_hotel" style="height: 150px;"/>

            <q-card-section>
              <q-btn
                fab
                color="primary"
                icon="place"
                class="absolute"
                style="top: 0; right: 12px; transform: translateY(-50%);" />

              <div class="row no-wrap items-center">
                <div class="col text-h6 ellipsis">
                  롯데 호텔 제주
                </div>
                <div class="col-auto text-grey text-caption q-pt-md row no-wrap items-center">
                  <q-icon name="place" />
                  서귀포
                </div>
              </div>

              <q-rating v-model="stars" :max="5" size="25px" />
            </q-card-section>

            <q-card-section class="q-pt-none">
              <div class="text-caption text-grey">
                "수영장이 매우 좋음"
              </div>
              <div class="text-subtitle1 text-red">
                117,187원~
              </div>
            </q-card-section>
            <q-separator />
            </q-card>
        </div>
      </q-carousel-slide>
            <q-carousel-slide :name="2" class="column no-wrap">
        <div class="row fit justify-start items-center q-gutter-xs q-col-gutter no-wrap">
          <q-card class="my-card">
            <q-img src="https://search.pstatic.net/common/?src=https://media.datahc.com/HI595096817.jpg&type=f1128_672_hotel" style="height: 150px;"/>

            <q-card-section>
              <q-btn
                fab
                color="primary"
                icon="place"
                class="absolute"
                style="top: 0; right: 12px; transform: translateY(-50%);" />

              <div class="row no-wrap items-center">
                <div class="col text-h6 ellipsis">
                  롯데 호텔 제주
                </div>
                <div class="col-auto text-grey text-caption q-pt-md row no-wrap items-center">
                  <q-icon name="place" />
                  서귀포
                </div>
              </div>

              <q-rating v-model="stars" :max="5" size="25px" />
            </q-card-section>

            <q-card-section class="q-pt-none">
              <div class="text-caption text-grey">
                "수영장이 매우 좋음"
              </div>
              <div class="text-subtitle1 text-red">
                117,187원~
              </div>
            </q-card-section>
            <q-separator />
            </q-card>
          <q-card class="my-card">
            <q-img src="https://search.pstatic.net/common/?src=https://media.datahc.com/HI595096817.jpg&type=f1128_672_hotel" style="height: 150px;"/>

            <q-card-section>
              <q-btn
                fab
                color="primary"
                icon="place"
                class="absolute"
                style="top: 0; right: 12px; transform: translateY(-50%);" />

              <div class="row no-wrap items-center">
                <div class="col text-h6 ellipsis">
                  롯데 호텔 제주
                </div>
                <div class="col-auto text-grey text-caption q-pt-md row no-wrap items-center">
                  <q-icon name="place" />
                  서귀포
                </div>
              </div>

              <q-rating v-model="stars" :max="5" size="25px" />
            </q-card-section>

            <q-card-section class="q-pt-none">
              <div class="text-caption text-grey">
                "수영장이 매우 좋음"
              </div>
              <div class="text-subtitle1 text-red">
                117,187원~
              </div>
            </q-card-section>
            <q-separator />
            </q-card>
          <q-card class="my-card">
            <q-img src="https://search.pstatic.net/common/?src=https://media.datahc.com/HI595096817.jpg&type=f1128_672_hotel" style="height: 150px;"/>

            <q-card-section>
              <q-btn
                fab
                color="primary"
                icon="place"
                class="absolute"
                style="top: 0; right: 12px; transform: translateY(-50%);" />

              <div class="row no-wrap items-center">
                <div class="col text-h6 ellipsis">
                  롯데 호텔 제주
                </div>
                <div class="col-auto text-grey text-caption q-pt-md row no-wrap items-center">
                  <q-icon name="place" />
                  서귀포
                </div>
              </div>

              <q-rating v-model="stars" :max="5" size="25px" />
            </q-card-section>

            <q-card-section class="q-pt-none">
              <div class="text-caption text-grey">
                "수영장이 매우 좋음"
              </div>
              <div class="text-subtitle1 text-red">
                117,187원~
              </div>
            </q-card-section>
            <q-separator />
            </q-card>
          <q-card class="my-card">
            <q-img src="https://search.pstatic.net/common/?src=https://media.datahc.com/HI595096817.jpg&type=f1128_672_hotel" style="height: 150px;"/>

            <q-card-section>
              <q-btn
                fab
                color="primary"
                icon="place"
                class="absolute"
                style="top: 0; right: 12px; transform: translateY(-50%);" />

              <div class="row no-wrap items-center">
                <div class="col text-h6 ellipsis">
                  롯데 호텔 제주
                </div>
                <div class="col-auto text-grey text-caption q-pt-md row no-wrap items-center">
                  <q-icon name="place" />
                  서귀포
                </div>
              </div>

              <q-rating v-model="stars" :max="5" size="25px" />
            </q-card-section>

            <q-card-section class="q-pt-none">
              <div class="text-caption text-grey">
                "수영장이 매우 좋음"
              </div>
              <div class="text-subtitle1 text-red">
                117,187원~
              </div>
            </q-card-section>
            <q-separator />
            </q-card>
          <q-card class="my-card">
            <q-img src="https://search.pstatic.net/common/?src=https://media.datahc.com/HI595096817.jpg&type=f1128_672_hotel" style="height: 150px;"/>

            <q-card-section>
              <q-btn
                fab
                color="primary"
                icon="place"
                class="absolute"
                style="top: 0; right: 12px; transform: translateY(-50%);" />

              <div class="row no-wrap items-center">
                <div class="col text-h6 ellipsis">
                  롯데 호텔 제주
                </div>
                <div class="col-auto text-grey text-caption q-pt-md row no-wrap items-center">
                  <q-icon name="place" />
                  서귀포
                </div>
              </div>

              <q-rating v-model="stars" :max="5" size="25px" />
            </q-card-section>

            <q-card-section class="q-pt-none">
              <div class="text-caption text-grey">
                "수영장이 매우 좋음"
              </div>
              <div class="text-subtitle1 text-red">
                117,187원~
              </div>
            </q-card-section>
            <q-separator />
            </q-card>
        </div>
      </q-carousel-slide>
    </q-carousel>
  </div>
</main>
</template>

<script>
import { ref } from 'vue'

export default {
 setup () {
    return {
      slide: ref(1)
    }
  }
}
</script>



<style lang="sass" scoped>
.my-card
  width: 100%
  max-width: 300px
  margin: 10px

</style>
