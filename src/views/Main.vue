<template>
  <div class="container">
    <div class="navbar"></div>
    <div class="section">
      <div class="sidebar"></div>
      <div class="content"></div>
    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
  .container{
    width: 100%;
    height: 100vh;
    display: flex;
    flex-direction: column;
    .navbar{
      width: 100%;
      height: 60px;
      background: blue;
      display: flex;
      justify-content: center;
      padding: 0 20px;
    }
    .section{
      width: 100%;
      height: calc(100% - 60px);
      display: flex;
      .sidebar{
        width: 25%;
        height: 100%;
        background: rgb(6, 6, 172);
      }
      .content{
        width: 75%;
        height: 100%;
        background: white;
        padding: 10px 25px;
      }
    }
  }
</style>
