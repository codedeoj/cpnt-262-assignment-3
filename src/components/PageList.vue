<script setup>
  const breeds = ([
    { breed: "Labrador Retriever" },
    { breed: "Bulldog" },
    { breed: "German Shepherd" },
    { breed: "Poodle" },
    { breed: "Beagle" }
  ])
</script>

<template>
  <ul>
    <li v-for="item in breeds" :key="item.id">
      {{ item.breed }} 
    </li>
  </ul>
</template>

<style scoped>

</style>