<template>
  <div class="about">
    <div class="logo-wrap">
      <a href="https://www.shijiezhou.com"><img alt="SZ logo" class="szlogo" src="../assets/logo j.gif"></a>
    </div>
    
    <section id="footer">
      <div class="container">
        <div class="">
          <p>
            Copyright ©
            <a href="https://www.shijiezhou.com">Shijie Zhou</a>
          </p>
        </div>
        <!-- // .desktop-3 -->
        <div class="clear"></div>
      </div>
      <!-- // .container -->
    </section>
  </div>
</template>

<script>
export default {
  
}
</script>

<style scoped>
.about{
  height: 800px;
}
.szlogo {
  width: 100px;
  height: 95px;
  border: 10px solid coral;
}

.szlogo:hover{
    -webkit-filter: invert(60%) !important;
}
</style>