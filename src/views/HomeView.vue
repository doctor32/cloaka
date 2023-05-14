<script setup>


</script>

<template>
  <main>
    <p>If you see this page you did something wrong</p>
    <p style="font-weight: 700;">Take a screenshot and send it to the owner</p>
<!--    <p>Please, wait 3-10 seconds...</p>-->
<!--    <div class="loader"></div>-->
  </main>
</template>

<style scoped >
p {
  text-align: center;
}
main {
  width: 100%;
  box-sizing: border-box;
  height: 80vh;
  display: flex;
  padding: 20px;
  align-items: center;
  justify-content: center;
  font-family: 'Arial', sans-serif;
  flex-direction: column;
}
.loader {
  background: #f8f171;
  width: 50px;
  height: 50px;
  border-radius: 50%;
  animation: loader 2s infinite;
}

@keyframes loader {
  0% {
    transform: scale(0);
  }
  100% {
    transform: scale(1);
  }
}
</style>
