<template>
  <div class="footer">
    <div class="footer-info">
      <my-logo></my-logo>
      <contact style="text-align: start"></contact>
    </div>
    <div class="footer-nav">
      <a href="#"
        ><img src="../static/images/facebookIcon.svg" alt="facebook"
      /></a>
      <a href="#"
        ><img src="../static/images/instaIcon.svg" alt="instagram"
      /></a>
      <a href="#"><img src="../static/images/VKIcon.svg" alt="VK" /></a>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.footer,
.footer-nav {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
}
.footer {
  padding: 42px 140px;
}
.footer-info {
  display: flex;
  justify-content: center;
  gap: 89px;
}
.footer-nav {
  gap: 12px;
}
</style>
