<template>
  <div id="app">
    <div class="home">
      <div class="h-top">
        <div class="logo center">Kuold</div>
      </div>
    </div>
    <router-view />
  </div>
</template>

<style lang="less">
#app {
  width: 100%;
  height: 100%;
  background: linear-gradient(to right, rgb(84, 74, 125), rgb(255, 212, 82));

  .home {
    
    .h-top {

      .logo {
        width: 200px;
        height: 80px;
        color: #caa95f;
        font-size: 48px;
        background-color: #454faf;
      }
    }
  }
}
</style>
