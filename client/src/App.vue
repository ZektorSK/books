<template>
  <HeaderC />
  <PromoC />
  <LatestC />
  <FooterC />
  <ReviewC />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HeaderC from './components/HeaderC.vue';
import PromoC from './components/PromoC.vue';
import LatestC from './components/LatestC.vue';
import FooterC from './components/FooterC.vue';
import ReviewC from './components/ReviewC.vue';

export default defineComponent({
  name: 'App',
  components: {
    HeaderC, LatestC, FooterC, ReviewC, PromoC
  }
});
</script>
