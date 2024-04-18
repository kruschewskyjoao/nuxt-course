<template>
  <div>
    We are inside a blog post!
  </div>
  <div>
    Post id is {{ route.params.id }}
  </div>
</template>


<script setup>
const route = useRoute()
</script>