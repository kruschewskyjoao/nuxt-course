<template>
  <div>
    This page is about me.
  </div>
  <div>
    <button @click="enableCustomLayout">
      Update layout
    </button>
  </div>
</template>

<script setup>
function enableCustomLayout() {
  setPageLayout('another')
}
</script>