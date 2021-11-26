<template>
  <v-app>
    <v-main>
      app js 
      <playground></playground>
    </v-main>
  </v-app>
</template>

<script>
  import Playground from './Playground'

  export default {
    components: {
      Playground,
    },
  }
</script>
