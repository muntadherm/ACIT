# ACIT
ACIT
<template>
  <div>
    <img :src="imageSrc" alt="Component Preview">
  </div>
</template>

<script>
export default {
  data() {
    return {
      imageSrc: require('@/assets/images/your-image.png'), // or use import
    };
  },
};
</script>

<style scoped>
/* Add component-specific styles here */
</style>
