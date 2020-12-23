<template>
  <div class="sidebar-header">
    <div class="sidebar-header__avatar"></div>
    <div class="sidebar-header__user">
      <div>John Doe</div>
      <div>In a meeting</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SidebarHeader",
};
</script>

<style>
.sidebar-header {
  border: solid 1px #000;
  padding: 5px;
}

.sidebar-header__avatar {
  display: inline-block;
  border: solid 1px #000;
  border-radius: 25px;
  height: 50px;
  width: 50px;
  vertical-align: middle;
}

.sidebar-header__user {
  padding-left: 10px;
  display: inline-block;
  width: calc(100% - 62px);
  vertical-align: middle;
}
</style>
