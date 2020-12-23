<template>
  <div class="sidebar">
    <side-bar-header />
    <side-bar-channels />
  </div>
</template>

<script>
import SideBarChannels from "./SideBarChannels.vue";
import SideBarHeader from "./SideBarHeader.vue";

export default {
  name: "SideBar",
  components: {
    SideBarHeader,
    SideBarChannels,
  },
};
</script>

<style>
.sidebar {
  position: fixed;
  top: 0;
  left: 0;
  bottom: 0;
  width: 300px;
  border: solid 1px #000;
}
</style>
