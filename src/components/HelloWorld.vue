<script>
import ImagesPageVue from "./ImagesPage.vue";
import ProfilePageVue from "./ProfilePage.vue";
export default {
  props: ["msg"],
  data() {
    return {};
  },
  components:{
    ImagesPageVue,
    ProfilePageVue
  }
};
</script>

<template>
  <ProfilePageVue/>
  <h1>{{ msg }}</h1>
  <ImagesPageVue/>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
