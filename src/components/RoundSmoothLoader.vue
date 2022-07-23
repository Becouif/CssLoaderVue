<template>
  <div>
    <p>Round Smooth loader</p>
    <div class="loader1"></div>
    <div class="loader2"></div>
  </div>
</template>

<style scoped>
@keyframes spin {
  to {
    transform: rotate(-360deg);
  }
}
@keyframes turn {
  to {
    transform: rotate(360deg);
  }
}
.loader1 {
  width: 64px;
  height: 64px;
  border-radius: 50%;
  border-top: 8px solid rgba(255, 255, 255, 1);
  border-left: 8px solid rgba(255, 255, 255, 1);
  border-right: 8px solid rgba(255, 255, 255, 0);
  animation: spin 0.575s infinite linear;
}
.loader2 {
  position: relative;
  width: 64px;
  height: 64px;
  border-radius: 50%;
  border-top: 8px solid rgba(255, 255, 255, 1);
  border-left: 8px solid rgba(255, 255, 255, 1);
  border-right: 8px solid rgba(255, 255, 255, 0);
  animation: turn 0.575s infinite linear;
}
</style>
