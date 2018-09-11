<template lang="">
  <div class="home-page">
    <section class="intro">
      <h1>Get the lastest tech news!</h1>
    </section>
    <section class="featured-posts">
      <nuxt-link :to="'/posts/' + 1">
        <article class="post-preview">
          <div class="post-thumbnail">
          </div>
          <div class="post-contnet">
            <h1> Post Title </h1>
            <p>Prev Text</p>
          </div>
        </article>
      </nuxt-link>
      <nuxt-link :to="'/posts/' + 2">
        <article class="post-preview">
          <div class="post-thumbnail">
          </div>
          <div class="post-contnet">
            <h1> Post Title 2</h1>
            <p>Prev Text 2</p>
          </div>
        </article>
      </nuxt-link>
    </section>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="css" scoped>

  .post-preview{
    border: 1px solid #ccc;
    box-shadow: 0 2px 2px #ccc;
    background-color: white;
    width: 90%;
  }

  a{
    text-decoration: none;
    color: black;
  }

  @media (min-width: 850px) {
    .post-preview{
      width: 400px;
      margin: 10px;
    }
  }

  .post-thumbnail{
    width: 100%;
    height: 200px;
    background-position: center;
    background-size: cover;
  }

</style>
