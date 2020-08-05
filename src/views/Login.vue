<template>
  <div class="container">
    <div class="sect">
      <div class="box1">\
        <h2>PAPERLESS</h2>
      </div>
      <div class="box2">
        <div class="headbox">
          <h2>Please Login to continue</h2>
        </div>
        <div class="input">
          <input type="text" id="username" placeholder="Username">
        </div>
        <div class="input">
          <input type="password" id="password" placeholder="Password">
        </div>
        <div class="buttonLogin">
          <button>Login</button>
        </div>
      </div>
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
    background: rgb(0, 0, 70);
    display: flex;
    justify-content: center;
    align-items: center;
    .sect{
      width: 780px;
      height: auto;
      background: white;
      display: flex;
      flex-wrap: wrap;
      .box1{
        width: 340px;
        height: 300px;
        background: rgb(6, 6, 177);
        display: flex;
        justify-content: center;
        align-items: center;
        h2{
          text-align: center;
          color: white;
          font-family: Arial, "Helvetica Neue", Helvetica, sans-serif;
        }
      }
      .box2{
        width: 440px;
        height: 300px;
        background: white;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        padding: 20px 30px;
        box-sizing: border-box;
        font-family: Arial, "Helvetica Neue", Helvetica, sans-serif;
        .headbox{
          color: rosybrown;
          padding: 20px 0;
          display: flex;
          justify-content: center;
          align-items: center;
          h2{
            text-align: center;
          }
        }
        .input{
          width: 100%;
          margin: 5px 0;
            input{
              box-sizing: border-box;
              padding-left: 45px;
              width: 100%;
              height: 40px;
              border: 1px solid rosybrown;
              outline: none;
              border-radius: 3px;
            }
        }
        .buttonLogin{
          margin: 20px 0;
          width: 100%;
          display: flex;
          justify-content: flex-end;
          button{
            width: 90px;
            height: 40px;
            background: rgb(6, 6, 177);
            color: white;
            border: none;
            border-radius: 3px;
            cursor: pointer;
            outline: none;
          }
        }
      }
    }
  }
  @media only screen and (max-width: 600px) {
    .container{
      box-sizing: border-box;
      padding: 0 20px;
    }
    .box1{
      height: 170px !important;
      width: 100% !important;
    }
    .box2{
      height: 350px !important;
      width: 100% !important;
    }
  }
</style>
