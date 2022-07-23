<template>
  <p>Pulse Loader</p>
  <div class="ploader"></div>
</template>

<style scoped>
@keyframes pulse {
  0% {
    transform: scale(0.15);
    opacity: 0;
  }
  50% {
    opacity: 1;
  }
  100% {
    transform: scale(1);
    opacity: 0;
  }
}
.ploader {
  width: 64px;
  height: 64px;
  border-radius: 50%;
  background: #ffffff;
  animation: pulse 0.85s infinite linear;
}
</style>
