<template>
  <div class="post">
    <h3>{{ post.title }}</h3>
    <p>{{ post.snippet }}</p>
  </div>


</template>

<script>
export default {
  props: ['post'],

}
</script>

<style>

.post {
  /* background: lightcoral; */
  width: 50vw;
  margin: 20px auto;
  padding: 10px;
  box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
  border-radius: 5px;
}

.post:hover {
  background: #eee;
  cursor: pointer;
}


</style>