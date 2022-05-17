<template>
    <nav class="sticky top-0 flex justify-center lg:gap-12 gap-5 w-auto h-[35px] bg-stone-100 shadow-lg mt-1">
        <a :class="TW_link" >Main Page <span class="lg:text-sm">˅</span></a>
        <a :class="TW_link">Database <span class="lg:text-sm">˅</span></a>
        <a :class="TW_link">About <span class="lg:text-sm">˅</span></a>
    </nav>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'App',
  data(){
      return{
          TW_link:'font-sans lg:text-xl text-lg font-semibold hover:underline hover:decoration-amber-500 hover:decoration-2 hover:text-amber-900 hover:cursor-pointer select-none'
      }
  }
});
</script>