<template>
  <Layout>



    <article>
      <header>
      <h2>{{$page.post.title}}</h2>
      <p>Published on {{$page.post.date}}</p>

      <p><i>{{$page.post.timeToRead}}min to read</i></p>
      </header>

      <main class="content" v-html="$page.post.content"></main>
    </article>
  </Layout>
</template>

<style>
article > header {
  text-align: center;
}

.content {
  margin-top: 48px;
  margin-left: 200px;
  color: black;
  font-size: 1.25rem;
}
</style>

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