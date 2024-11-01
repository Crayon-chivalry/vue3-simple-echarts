<template>
  <div class="dashboard">
    <div class="col-3 card"></div>
    <div class="col-6 column">
      <div class="card col-3"></div>
      <div class="card col-6"></div>
    </div>
    <div class="col-3 card"></div>
  </div>
</template>

<script setup>
</script>

<style scoped>
.dashboard {
  padding: 10px;
  width: 100vw;
  height: 100vh;
  background-image: url('@/assets/image/bg.jpg');
  background-size: cover;
  background-position: center;
  display: flex;
  gap: 10px;
  box-sizing: border-box;
}

.card {
  background-color: rgb(30 41 59 / .5);
}

.column {
  display: flex;
  flex-direction: column;
  row-gap: 10px;
}

.col-3 {
  flex: 3;
}

.col-6 {
  flex: 6;
}
</style>