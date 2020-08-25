<template>
  <!--<div class="background" :style="{ backgroundImage: `url(${backgroundUrl})` }">-->
  <div>
    <Nav>
    </Nav>
    <div class="main-body">
    <h1 class="home-title">I'm Seppe</h1>
    <h2 class="home-title">FullStack Developer & Electronics Engineer</h2>
    </div>
  </div>
</template>

<script>
import backgroundUrl from '~/assets/back.jpg'
export default {
  data() {
    return { backgroundUrl }
  }
}
</script>

<style>
  .home-title{
    display: flex;
    justify-content: center;
    color: white;
  }
.background-image{
  opacity: 0.3;
}
.main-body{
  /*background-image: url('~/assets/back.jpg');*/
  background-repeat: no-repeat;
  height: 120%;
  widows: 120%;
}
</style>
