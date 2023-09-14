<template>
  <div v-for="post in posts">
    <router-link to="posts" class="router-link">
      <BlogPost :post="post" :key="post.id" />
    </router-link>
    
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

.router-link {
  text-decoration: none;
  color: inherit;
}
</style>