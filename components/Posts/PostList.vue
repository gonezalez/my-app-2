<template>
    <section class="post-list">
      <PostPreview
        id="1"
        thumbnail="https://www.visioncritical.com/wp-content/uploads/2015/12/tech-companies-resources-950x700.jpg"
        title="Qlq 1"
        previewText="Qlq Ep.1"
        />
      <PostPreview
        id="2"
        thumbnail="https://www.visioncritical.com/wp-content/uploads/2015/12/tech-companies-resources-950x700.jpg"
        title="Qlq 2"
        previewText="Qlq Ep.2"
        />
      <PostPreview
        id="3"
        thumbnail="https://www.visioncritical.com/wp-content/uploads/2015/12/tech-companies-resources-950x700.jpg"
        title="Qlq 3"
        previewText="Qlq Ep.3"
        />
    </section>
</template>

<script>

import PostPreview from '@/components/Posts/PostPreview';

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
