<template>
  <div class="navbar">
    <ul>
      <li><a href="#">HOME</a></li>
      <li><a href="#">SERVICES</a></li>
      <li><a href="#">BLOG</a></li>
      <li><a href="#">ABOUT</a></li>
      <li><a href="#">CONTACT</a></li>
    </ul>
  </div>
</template>

<style scoped>
  .navbar {
    background-color: #000;
    height: 40px;
    padding-left: 100px;
  }
  .navbar ul {
    list-style: none;
    margin: 0;
    padding: 0;
  }
  .navbar ul li {
    float: left;
  }
  .navbar ul li a {
    display: block;
    padding: 10px;
    text-decoration: none;
    color: #fff;
  }
</style>