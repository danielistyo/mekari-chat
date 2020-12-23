<template>
  <div class="channels">
    <div class="channels__title">Channels</div>
    <div class="channels__list">
      <div
        v-for="(channel, key) in channels"
        :key="key"
        class="channels__single"
      >
        {{ channel }}
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SideBarChannels",
  data() {
    return {
      channels: ["#general", "#engineering"],
    };
  },
};
</script>

<style>
.channels {
  padding: 5px;
}

.channels__title {
  font-weight: bold;
}

.channels__list {
  margin-top: 5px;
  margin-left: 5px;
}
</style>
