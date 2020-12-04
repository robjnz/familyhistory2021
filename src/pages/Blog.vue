<template>
  <Layout>
    <section
      id="container-centre"
      class="column centre flex-1 px-32 py-14 overflow-auto"
    >
      <h1 class="page-title text-center">Blog</h1>
      

      <BlogPostList :posts="$page.posts.edges" />
    </section>
  </Layout>
</template>

<script>
import BlogPostList from "~/components/BlogPostList.vue";

export default {
  metaInfo: {
    title: "Blog",
  },
  components: {
    BlogPostList,
  },
};
</script>

<page-query>
query {
  posts: allBlogPost {
    edges {
      node {
        id
        title
        date (format: "MMMM D, YYYY")
        path
      }
    }
  }
}
</page-query>
