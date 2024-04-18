<template>
  <div>Projects</div>
</template>

<script setup>
const callApi = await useFetch('https://api.github.com/users/piotr-jura-udemy/repos');
console.log(callApi);
</script>