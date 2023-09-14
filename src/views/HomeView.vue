<template>
  <div class="home">
    <h1>Homepage</h1>
    <div v-for="post in posts">
      <p> {{ posts[0].title }}</p>
    </div>

  </div>
</template>

<script>
import { ref } from 'vue';

export default {
  name: 'HomeView',
  setup() {
    const posts = ref([
      { title: 'Blog Post 1', snippet: 'This is blog post 1.', body: 'This is body 1.', id: 1},
      { title: 'Blog Post 2', snippet: 'This is blog post 2.', body: 'This is body 2.', id: 2},
      { title: 'Blog Post 3', snippet: 'This is blog post 3.', body: 'This is body 3.', id: 3},
    ])

    return { posts }
  }

}
</script>
