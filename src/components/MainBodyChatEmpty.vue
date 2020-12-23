<template>
  <div class="empty-state">
    <div class="empty-state__avatar"></div>
    <div class="empty-state__user">
      <div>John Doe</div>
      <div>Hei, do not see anyone in the room</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainBodyChatEmpty",
};
</script>

<style>
.empty-state {
  border-top: solid 1px #000;
  padding-top: 15px;
}

.empty-state__avatar {
  display: inline-block;
  border: solid 1px #000;
  height: 50px;
  width: 50px;
  vertical-align: middle;
}

.empty-state__user {
  padding-left: 10px;
  display: inline-block;
  width: calc(100% - 62px);
  vertical-align: middle;
}
</style>
