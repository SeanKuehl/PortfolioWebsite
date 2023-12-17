<script setup>
defineProps({
  imagePath: {
    type: String,
    required: true
  },
  uniformSize: {
    type: String,
    required: true
  },
  message: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="itemDisplay">
    <img :src="imagePath" :width="uniformSize" :height="uniformSize" />
    <p>{{ message }}</p>
  </div>
</template>

<style scoped>
.itemDisplay {
  display: flex;
}
</style>
