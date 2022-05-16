<template>
    <nav class="flex justify-center gap-12 w-auto h-[30px] bg-stone-100">
        <a :class="TW_link" >Main Page</a>
        <a :class="TW_link">Database</a>
        <a :class="TW_link">About</a>
    </nav>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'App',
  data(){
      return{
          TW_link:'font-sans text-lg font-semibold hover:underline hover:decoration-amber-500 hover:decoration-2 hover:text-xl hover:text-amber-900'
      }
  }
});
</script>