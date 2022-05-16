<template>
  <headerC />
  <NavbarC />
  <MainPromoC />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HeaderC from './components/HeaderC.vue';
import NavbarC from './components/NavbarC.vue';
import MainPromoC from './components/MainPromoC.vue';

export default defineComponent({
  name: 'App',
  components: {
    HeaderC, NavbarC, MainPromoC
  }
});
</script>
