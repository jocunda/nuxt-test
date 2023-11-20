<template>
  <div>
    <p>Product Detail for {{ id }}</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus illum quas et beatae rerum, explicabo nobis neque reiciendis, mollitia cum, possimus itaque earum cumque quae soluta voluptates veritatis qui fugit.</p>
  </div>
</template>

<script setup>
  const { id }=useRoute().params
</script>

<style scoped>

</style>