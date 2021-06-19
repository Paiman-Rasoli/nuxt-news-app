<template>
  <div class="container">
    <div class="row">
      <Post
        v-for="article in articles"
        :key="article.title"
        :postProp="article"
      />
    </div>
  </div>
</template>

<script>
export default {
  // use this for using SSR(server side rendering)
  async asyncData() {
    const apiKey = "9e500acbec4c45b6b0ecbb132de0d02c";

    const posts = await fetch(
      `https://newsapi.org/v2/top-headlines?sources=bbc-news&apiKey=${apiKey}`
    ).then(data => data.json());
    //get 9 articles
    const articles = posts.articles.slice(0, 9);
    return { articles };
  }
};
</script>
<style scoped></style>
