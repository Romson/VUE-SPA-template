<template>
  <div class="container float-right">
    <ul>
      <li>Home</li>
      <li>About</li>
      <li>Blog</li>
      <li>Contact</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Menu'
}
</script>

<style lang="scss" scoped>
ul {
  margin-top: 0;

  & li {
    display: inline-block;
    list-style: none;
    padding: 20px;
  }
}
</style>