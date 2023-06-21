<template>
  <v-app>
    <Infomation />
  </v-app>
</template>

<script>
import Infomation from "@/Infomation";

export default {
  name: "App",

  components: {
    Infomation,
  },

  data: () => ({
    //
  }),
};
</script>

<style>
#app {
  margin: 0;
  background: #ccc;
}
</style>
