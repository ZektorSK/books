<template>
  <headerC />
  <NavbarC />
  <MainPromoC />
  <LatestC />
  <FooterC />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HeaderC from './components/HeaderC.vue';
import NavbarC from './components/NavbarC.vue';
import MainPromoC from './components/MainPromoC.vue';
import LatestC from './components/LatestC.vue';
import FooterC from './components/FooterC.vue';

export default defineComponent({
  name: 'App',
  components: {
    HeaderC, NavbarC, MainPromoC, LatestC, FooterC
  }
});
</script>
