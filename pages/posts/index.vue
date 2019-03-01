<template>
<PostList />
</template>

<script>
import PostList from '@/components/Posts/PostList'

export default {
  components: {
    PostList
  }
}
</script>

<style scoped>
.posts-page {
  text-align: center;
  padding: 30px;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
