<template>
<section class="post-list">
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
</template>

<script>
import PostPreview from '@/components/Posts/PostPreview'

export default {
  components: {
    PostPreview
  }
}
</script>

<style scoped>
.post-list {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
</style>
