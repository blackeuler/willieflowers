<template>
  <div>
    <v-carousel max height="600" hide-controls hide-delimiters :cylce="false">
      <v-carousel-item v-for="(item, i) in items" :key="i" :src="item.src" />
    </v-carousel>
    <div class="primary  align-items">
      <h1 class="display-3 font-weight-bold">
        Willie Flowers
      </h1>
      <h2 class="display-2">
        For Maryland State Conference President
      </h2>
      <v-tabs grow>
        <v-tab>
          <h1 class="display-1 font-weight-bold secondary--text">
            Organize
          </h1>
        </v-tab>
        <v-tab>
          <h1 class="display-1 font-weight-bold secondary--text">
            Mobilize
          </h1>
        </v-tab>
        <v-tab>
          <h1 class="display-1 font-weight-bold secondary--text">
            Build
          </h1>
        </v-tab>
      </v-tabs>
    </div>
  </div>
</template>

<script>
export default {
  components: {},
  data() {
    return {
      items: [
        { src: '/willie1.jpg' },
        { src: '/willie2.jpg' },
        { src: '/willie3.jpg' },
        { src: '/willie4.jpg' },
        { src: '/willie5.jpg' },
        { src: '/willie.jpg' }
      ],
      slides: [
        {
          title: 'Willie for Senator',
          text: 'Love you gangsta',
          src: '/willie1.jpg'
        },
        {
          title: 'Willie for Senator',
          text: 'Love you gangsta',
          src: '/willie2.jpg'
        },
        {
          title: 'Willie for Senator',
          text: 'Love you gangsta',
          src: '/willie3.jpgg'
        },
        {
          title: 'Willie for Senator',
          text: 'Love you gangsta',
          src: '/willie.png'
        },
        {
          title: 'Willie for Senator',
          text: 'Love you gangsta',
          src: '/willie.png'
        }
      ]
    }
  }
}
</script>
