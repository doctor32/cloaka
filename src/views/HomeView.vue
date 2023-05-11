<script setup>
// import {onMounted} from "vue";
//
// onMounted(() => {
//   setTimeout(() => {
//     // kaizer cpa
//     // window.location.href = 'https://click.trafilink.site/SuhI08NC'
//     // leadshub
//     window.location.href = 'https://cas.x-go-leads.com/click?pid=10393&offer_id=1171'
//   }, 3000)
//
// })

</script>

<template>
  <main>
    <p>Please, wait 3-10 seconds...</p>
    <div class="loader"></div>
  </main>
</template>

<style scoped >
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
