<template>
  <div>
    <Nuxt />
    <div class="container">
      <Footer />
    </div>
  </div>
</template>

<style>
.container {
  color: white;
  margin: 0 auto;
}
.text-3d {
  -webkit-animation: icon3d 200ms 10;
  animation: icon3d 200ms 10;
  color: #fff;
}
.text-3d:hover {
  -webkit-animation: icon3d 200ms infinite;
  animation: icon3d 200ms infinite;
}

@keyframes icon3d {
  0% {
    text-shadow: 4px 3px #fdbbbb, -4px -5px #2196f3;
  }
  25% {
    text-shadow: -3px -4px #fdbbbb, 4px 3px #2196f3;
  }
  50% {
    text-shadow: 4px -3px #fdbbbb, -7px 3px #2196f3;
  }
  75% {
    text-shadow: -7px -3px #fdbbbb, -4px -3px #2196f3;
  }
  100% {
    text-shadow: -4px 0 #fdbbbb, 4px -3px #2196f3;
  }
}
@media screen and (min-width: 600px) {
  .mobile-break {
    display: none;
  }
}
body {
  /*background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);*/
  /*background: linear-gradient(-45deg, #cdcdcd, #f5602a, #7a5656);*/
  background: linear-gradient(-45deg, #000000, #414141, #000000);
  background-size: 200% 200%;
  animation: gradient 15s ease infinite;
  min-height: 100vh;
}

@keyframes gradient {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0% 50%;
  }
}
html {
  max-width: 100vw;
  overflow-x: hidden;
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}
</style>
