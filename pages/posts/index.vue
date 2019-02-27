<template>
  <div class="posts-page">
    <input type="text" v-model="postId">
    <button @click="onLoadUser">Find Post</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      postId: ""
    };
  },
  methods: {
    onLoadUser() {
      this.$router.push("/posts/" + this.postId);
    }
  }
};
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
