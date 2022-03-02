<template>
    <footer class="footer" >

   </footer>
  </template>

<script>
export default {
  name: "Footer",
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.footer {
  position: absolute;
    bottom: 0;
    width: 120%;
    height: 60px;
    line-height: 60px;
    background-color: #000;
}
</style>
