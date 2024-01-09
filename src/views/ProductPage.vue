<!-- views/ProductPage.vue -->
<template>
  <div>
    <!-- Include your components -->
    <Header />
    <ProductImage />
    <ProductInfo />
    <PopupViewer />
    <Thumbnails />
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import ProductImage from '@/components/ProductImage.vue';
import ProductInfo from '@/components/ProductInfo.vue';
import PopupViewer from '@/components/PopupViewer.vue';
import Thumbnails from '@/components/Thumbnails.vue';

export default {
  components: {
    Header,
    ProductImage,
    ProductInfo,
    PopupViewer,
    Thumbnails,
  },
  // Main view logic
};
</script>

<style scoped>
/* Your view-specific styles */
</style>
