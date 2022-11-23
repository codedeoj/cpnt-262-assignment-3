<script setup>
defineProps({
  title: {
    type: String,
    default: "Website Header",
  },
  description: {
    type: String,
    default: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque lobortis magna sed massa tempor rhoncus."
  }
});
</script>

<template>
  <div class="header">
    <h1> {{ title }} </h1>
    <p> {{ description }} </p>
    <slot name="text"></slot>
  </div>
</template>

<style scoped>
.header {
  min-height:250px;
  background: pink;
  margin:0;
  padding:0;
}
.header h1 {
  text-align:center;
  padding-top: 50px;
  margin: 0;
  color: #fff;
  font-size: 60px;
}
.header p {
  text-align:center;
  color: #fff;
  max-width: 50ch;
  margin: auto;
  font-size: 22px;
}
</style>