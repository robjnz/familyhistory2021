<template>
  <section
    id="container-centre"
    class="column centre flex-1 px-6 py-14 overflow-auto"
  >
   
    <div class="work-card mb-6" v-for="post in posts" :key="post.node.id">
      <h4 class="text-red-900 text-2xl">{{ post.node.title }}</h4>
      <p class="text-gray-900 text-xl"> {{ post.node.excerpt }}</p>
      <br />
      <p class="text-gray-900 text-lg">Published on {{ post.node.date }}</p>
      <g-link class="text-blue-700 text-2xl" :to="post.node.path">Read article</g-link>
    </div>
   
   
      
  </section>
</template>

<script>
export default {
 


metaInfo: {
    title: "blog posts",
    meta: [
      {
        name: "description",
        content:
          "Blog posts",
      },
    ],
  },
   props: ["posts"],
}
</script>

<style>
.post-list {
  margin-top: 12px;
}

.post {
  padding: 12px 0;
}
</style>