<template>
  <div id="app">
    <side-bar />
    <main-body />
  </div>
</template>

<script>
import SideBar from "./components/SideBar.vue";
import MainBody from "./components/MainBody.vue";

export default {
  name: "App",
  components: {
    MainBody,
    SideBar,
  },
};
</script>
