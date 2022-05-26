<template>
  <HeaderC />
  <PromoC />
  <MainC />
  <FooterC />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HeaderC from './components/HeaderC.vue';
import PromoC from './components/PromoC.vue';
import MainC from './components/MainC.vue';
import FooterC from './components/FooterC.vue';

export default defineComponent({
  name: 'App',
  components: {
    HeaderC, MainC, FooterC, PromoC
  }
});
</script>
