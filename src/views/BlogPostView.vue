<template>
  <h3>You're reading a single blog post</h3>
  <h3>{{ id }}</h3>
  <!-- <p> {{ post }}</p> -->
  <p></p>
</template>

<script>
export default {
  props: ['id', 'post'],
}
</script>

<style>

</style>