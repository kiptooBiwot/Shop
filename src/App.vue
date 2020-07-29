<template>
  <v-app>
    <div id="nav">
      <router />
    </div>
    <router-view />
  </v-app>
</template>

<script>
import Router from './components/TopNavBar.vue';

export default {
  name: 'App',

  components: {
    Router,
  },

  data: () => ({
    //
  }),
};
</script>
