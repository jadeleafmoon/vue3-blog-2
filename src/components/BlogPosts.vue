<template>
  <div v-for="post in posts">
    <BlogPost :post="post" :key="post.id" />
  </div>

</template>

<script>
import BlogPost from './BlogPost.vue'

export default {
  props:['posts'],
  components: { BlogPost }

}
</script>

<style>

</style>