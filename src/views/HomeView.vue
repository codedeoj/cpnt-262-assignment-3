<script setup>
import PageHeader from "../components/PageHeader.vue";
import PageList from "../components/PageList.vue";
</script>

<template>
  <PageHeader>
    <template v-slot:text>
      <button class="btn">
        Click Here!
      </button>
    </template>
  </PageHeader>
  
  <PageList />
</template>

<style scoped>
  .btn {
    display: block;
    margin: auto;
    margin-top: 20px;
    padding: 10px 18px;
    font-weight: bold; 
    background-color: #330cdf;
    color: #fff;
    cursor: pointer;
    border-radius: 5px;
    border: none;
    transition: 0.2s all;
  }
  .btn:hover {
    transform: scale(0.9);
  }
</style>