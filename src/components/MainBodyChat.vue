<template>
  <div class="main-body-chat">
    <div class="main-body-chat__messages"></div>
    <div class="main-body-chat__wrapper-input">
      <main-body-chat-empty />
      <input class="main-body-chat__input" placeholder="Message to general" />
    </div>
  </div>
</template>

<script>
import MainBodyChatEmpty from "./MainBodyChatEmpty.vue";
export default {
  components: { MainBodyChatEmpty },
  name: "MainBodyChat",
};
</script>

<style>
.main-body-chat {
  width: 100%;
  height: 100%;
  margin: 20px 10px;
}

.main-body-chat__wrapper-input {
  display: block;
  position: absolute;
  bottom: 20px;
  right: 10px;
  left: 10px;
  width: calc(100% - 40px);
}

.main-body-chat__input {
  width: 100%;
  height: 40px;
  margin-top: 20px;
}
</style>
