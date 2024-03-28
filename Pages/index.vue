<template>
    <div>
      <h1>Welcome to the homepage</h1>
      <NavBar />
      <WelcomeBanner />
      <AppAlert>
        This is an auto-imported component
      </AppAlert>
    </div>
  </template>
  <script>
  import NavBar from '~/components/NavBar.vue'
  import WelcomeBanner from '~/components/WelcomeBanner.vue'
  export default {
    components: {
      NavBar,
      WelcomeBanner
    }
  }
  </script>