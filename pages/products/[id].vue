<template>
  <div>
    <p>Product details for {{ id }}</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem amet a totam, tempore dolorem perferendis ipsum quis iusto ratione reiciendis!</p>
  </div>
</template>

<script setup>

    const { id } = useRoute().params

</script>

<style scoped>

</style>