<template>
  <div class="main-body">
    <main-body-header />
    <main-body-chat />
  </div>
</template>

<script>
import MainBodyChat from "./MainBodyChat.vue";
import MainBodyHeader from "./MainBodyHeader.vue";
export default {
  components: { MainBodyHeader, MainBodyChat },
  name: "MainBody",
};
</script>

<style>
.main-body {
  position: fixed;
  top: 0;
  right: 0;
  left: 300px;
  bottom: 0;
}
</style>
