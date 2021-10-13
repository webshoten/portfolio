<template>
  <v-app dark>
    <v-app-bar
      :clipped-left="clipped"
      fixed
      elevate-on-scroll
      color="white"
      app
    >
    <v-row justify="left">
      <v-app-bar-nav-icon
       to="/"
      >
        <v-icon large>mdi-book-open-variant</v-icon>
      </v-app-bar-nav-icon>
      <v-app-bar-nav-icon
       to="/profile"
       nuxt
      >
        <v-icon large>mdi-face-man-profile</v-icon>
      </v-app-bar-nav-icon>
    </v-row>
    </v-app-bar>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
  </v-app>
</template>
<script>
export default {
  data () {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: 'mdi-apps',
          title: 'Recently',
          to: '/'
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Inspire',
          to: '/inspire'
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'φ'
    }
  }
}
</script>
