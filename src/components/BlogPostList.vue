<template>
  <section
    id="container-centre"
    class="column centre flex-1 px-32 py-14 overflow-auto"
  >
    <div class="work-card mt-6" v-for="post in posts" :key="post.node.id">
      <h4 class="text-red-900">{{ post.node.title }}</h4>
      <p class="text-gray-900">Published on {{ post.node.date }}</p>
      <g-link class="text-blue-700" :to="post.node.path">Read article</g-link>
    </div>
  </section>
</template>

<script>
export default {
  props: ["posts"],
};
</script>

<style>
.post-list {
  margin-top: 12px;
}

.post {
  padding: 12px 0;
}
</style>
