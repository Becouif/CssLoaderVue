<template>
  <p>Glass Loader</p>
  <div class="loader"></div>
</template>

<style scoped>
.loader {
  transform: perspective(140px) rotateX(-50deg);
  width: 32px;
  height: 72px;
  position: relative;
  border: 2px solid #fff;
  animation: load 1.6s linear infinite alternate;
}

@keyframes load {
  0% {
    box-shadow: 0 0 #ed3b65 inset;
  }
  50% {
    box-shadow: 0 0 #fff inset;
  }
  75% {
    box-shadow: 0 0 #fff inset;
  }
  100% {
    box-shadow: 0 -70px #ed3b65 inset;
  }
}
</style>
