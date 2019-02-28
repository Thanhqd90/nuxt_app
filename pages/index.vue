<template>
  <div class="home-page">
    <section class="intro">
      <h1>Home Page</h1>
    </section>
    <section class="featured-posts">
      <PostPreview
      id="1"
      thumbnail="https://www.goodfood.com.au/content/dam/images/h/0/f/a/q/i/image.related.wideLandscape.940x529.h0fa4n.png/1515456591895.jpg"
      title="Post 1"
      previewText="This is post 1" />
      <PostPreview
      id="2"
      thumbnail="https://static.independent.co.uk/s3fs-public/thumbnails/image/2017/02/07/15/chinese.jpg?w968h681"
      title="Post 2"
      previewText="This is post 2" />      
      <PostPreview
      id="3"
      thumbnail="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRI2xb-55P8uByCC-AlGem22JTzO8ZUrTeCaE74iHGEj5w92i-N"
      title="Post 3"
      previewText="This is post 3" />
    </section>
  </div>
</template>

<script>
import PostPreview from '@/components/Posts/PostPreview'

export default {
  components: {
    PostPreview
  }
}
</script>

<style>
.intro {
  height: 300px;
  position: relative;
  padding: 30px;
  box-sizing: border-box;
  background-image: url('~assets/images/main-page-background.jpg');
  background-position: center;
  background-size: cover;
}

.intro h1 {
  position: absolute;
  top: 10%;
  left: 5%;
  width: 90%;
  font-size: 1.5rem;
  color: black;
  background-color: rgb(211, 211, 211);
  padding: 10px;
  border-radius: 10px;
  box-shadow: 3px 3px 3px black;
  box-sizing: border-box;
  border: 1px solid black;
}

@media (min-width: 768px) {
  .intro h1 {
    font-size: 2rem;
  }
}

.featured-posts {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
</style>
