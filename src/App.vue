<template>
  <div class="container">
    <HeaderArea></HeaderArea>
    <div class="content">
      <p>Test content...</p>
    </div>
    <FooterArea></FooterArea>
  </div>
</template>

<script>
import HeaderArea from '@/components/header/HeaderArea.vue';
import FooterArea from '@/components/footer/FooterArea.vue';

export default {
  name: 'App',
  components: {
    FooterArea,
    HeaderArea,
  },
};
</script>

<style>
.container {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

.content {
  flex: 1;
}
</style>
