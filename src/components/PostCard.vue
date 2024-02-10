<script lang="ts" setup>
import PostButton from "./PostButton.vue";
</script>

<template>
  <div class="post-card">
    <h3>Título</h3>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae
      suscipit aperiam veritatis fuga impedit
    </p>
    <PostButton />
  </div>
</template>

<style scoped>
.post-card {
  border-radius: 15px;
  padding: 10px;
  margin: 5px;
  border: 1px solid #ccc;
}
</style>
