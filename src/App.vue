<template>
  <div class="QRBlock">
    <img class="qrcodeimg" src="./assets/image-qr-code.png" alt="qrcode">
    <h1>Lorem, ipsum.</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque, et.
    </p>
  </div>
</template>

<script>

export default {
  name: 'App'
}
</script>

<style>
  body{
    background-color: hsl(212, 45%, 89%);
  }
#app {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  font-family: 'Outfit', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.QRBlock{
  font-size: 15px;
  border-radius: 15px;
  height: 65vh;
  width: 75vw;
  background-color: hsl(0, 0%, 100%);
}
.qrcodeimg{
  margin-top: 2vh;
  width: 65vw;
  border-radius: 12px;
}

@media screen and (min-width: 1024px) {
  .QRBlock{
    height: 65vh;
    width: 20vw;
  }
  .qrcodeimg{
    width: 19vw;
  }
}
</style>
