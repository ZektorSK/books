<template>
  <headerC />
  <NavbarC />
  <MainPromoC />
  <LatestC />
  <FooterC />
  <ReviewC />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HeaderC from './components/HeaderC.vue';
import NavbarC from './components/NavbarC.vue';
import MainPromoC from './components/MainPromoC.vue';
import LatestC from './components/LatestC.vue';
import FooterC from './components/FooterC.vue';
import ReviewC from './components/ReviewC.vue';

export default defineComponent({
  name: 'App',
  components: {
    HeaderC, NavbarC, MainPromoC, LatestC, FooterC, ReviewC
  }
});
</script>
