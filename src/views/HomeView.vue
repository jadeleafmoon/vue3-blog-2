<template>
  <div class="home">
    <h1>Barty's Blog</h1>
    <BlogPosts :posts="posts"/>
  </div>
</template>

<script>
import BlogPosts from '../components/BlogPosts.vue'
import { ref } from 'vue'

export default {
  name: 'HomeView',
  components: { BlogPosts },
  setup() {
    const posts = ref([
      { title: 'Blog Post 1', snippet: 'This is a snippit for Blog Post 1.', body: "This is the body of Blog 1. Charlie and the Chocolate Factory by Roald Dahl tells the tale of Charlie Bucket, a poor boy who lives near Willy Wonka's renowned chocolate factory. Willy Wonka hides golden tickets inside five of his chocolate bars, granting bearers a tour of his factory. The world becomes obsessed with finding these tickets. Against all odds, Charlie discovers one. He joins the other winners for a tour filled with wondrous rooms and the unique Oompa-Loompas. As the children face various temptations and challenges inside the factory, Charlie proves to be different, leading to a heartwarming conclusion.", id: 1},
      { title: 'Blog Post 2', snippet: 'This is a snippit for Blog Post 2.', body: "This is the body of Blog 2. Charlie and the Chocolate Factory by Roald Dahl tells the tale of Charlie Bucket, a poor boy who lives near Willy Wonka's renowned chocolate factory. Willy Wonka hides golden tickets inside five of his chocolate bars, granting bearers a tour of his factory. The world becomes obsessed with finding these tickets. Against all odds, Charlie discovers one. He joins the other winners for a tour filled with wondrous rooms and the unique Oompa-Loompas. As the children face various temptations and challenges inside the factory, Charlie proves to be different, leading to a heartwarming conclusion.", id: 2},
      { title: 'Blog Post 3', snippet: 'This is a snippit for Blog Post 3.', body: "This is the body of Blog 3. Charlie and the Chocolate Factory by Roald Dahl tells the tale of Charlie Bucket, a poor boy who lives near Willy Wonka's renowned chocolate factory. Willy Wonka hides golden tickets inside five of his chocolate bars, granting bearers a tour of his factory. The world becomes obsessed with finding these tickets. Against all odds, Charlie discovers one. He joins the other winners for a tour filled with wondrous rooms and the unique Oompa-Loompas. As the children face various temptations and challenges inside the factory, Charlie proves to be different, leading to a heartwarming conclusion.", id: 3},
    ])

    return { posts }
  }

}
</script>
