<template>
  <div class="con" >
    <h1>AGROPULS3</h1>
    <ul >
      <li><a href="#">home</a></li>
      <li><a href="#">about</a></li>
      <li><a href="#">contacts</a></li>
    </ul>


  </div>
  
  
</template>
<script setup></script>

<style scoped>

  .con {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 20px;
    background-color: green;
    color: white;
  }
  h1 {
    font-size: 24px;
  }
  ul {
    list-style: none;
    display: flex;
  }
  li {
    margin-right: 10px;
  }
</style>
