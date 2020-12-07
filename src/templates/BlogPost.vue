<template>
  <Layout>
    <article>
      <header class="mt-6">
        <h2>{{ $page.post.title }}</h2>
        <p>Published on {{ $page.post.date }}</p>

        <p>
          <i>{{ $page.post.timeToRead }}min to read</i>
        </p>
      </header>

      <main class="prose-sm blog-card overflow-auto" v-html="$page.post.content"></main>
    </article>
  </Layout>
</template>

<style>
article > header {
  text-align: center;
}

.content1 {
  margin-top: 48px;
  margin-left: 200px;
  color: black;
  font-size: 1.25rem;
}

.blog-card {
  box-shadow: 0px 0px 20px rgba(0, 0, 0.1);
  padding: 5rem;
  border-radius: 0.2rem;
  color: black;
  font-size: 1.5rem;
  font-family: Roberto;
  margin-left: 20%;
  margin-right: 20%;
  margin-bottom: 10%;
  margin-top: 2%;
  text-align: left;
}
</style>

<script>

export default {
  metaInfo: {
    title: "Posts",
    meta: [
      {
        name: "description",
        content:
          "Blog posts",
      },
    ],
  },
  components: {
    
    
  },
};
</script>


<page-query>
query Post ($path: String!) {
   post: blogPost (path: $path) {
    id
    title
    date (format: "MMMM D, YYYY")
    timeToRead
    content
  }
}
</page-query>
