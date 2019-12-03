<template>
  <div class="container-fluid header-container">
    <Menu />
  </div>
</template>

<script>
import Menu from './Menu.vue';

export default {
  components: { Menu }
}
</script>

<style lang="scss" scoped>
  .header-container {
    background-color: #eef4f5;
    overflow: hidden;
  }
</style>