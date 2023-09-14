<template>
  <div class="blog-container">
    <div class="blog-card"> 
      <h2>{{ title }}</h2>
      <p>{{ body }}</p>
    </div>
  </div>


  
  <p></p>
</template>

<script>
export default {
  props: ['id', 'title', 'body'],
}
</script>

<style>

.blog-container {
  width: 80vw;
  max-width: 800px;
  margin: 20px auto;
}

.blog-card {
  background: white;
  border-radius: 5px;
  margin: 10px;
  padding: 20px;
  text-align: left;
  box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
}


</style>