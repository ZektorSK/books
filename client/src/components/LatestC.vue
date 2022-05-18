<template>
    <div class="flex flex-col justify-center items-center">
        <article class="flex flex-col justify-center items-center mt-8 max-w-[800px]">
            <h2 class="font-tahoma text-5xl text-center font-bold">Bringing the <span class="bg-black text-white">latest</span> titles to you...</h2>

            <div class="flex flex-row justify-center items-center gap-8 mt-8">
                <img src="../assets/book_taipan.jpg" v-show="deviceW > 768" class="h-[350px] w-[250px] opacity-50 hover:opacity-80 hover:cursor-pointer hover:shadow-lg transition-opacity ease-in-out">

                <img src="arrow" v-show="deviceW < 768">
                <figure class="">
                    <img src="../assets/book_metro.jpg" class="h-[300px] w-[250px] md:h-[350px] md:w-[250px] border-b-4 border-amber-500 shadow-lg" title="METRO 2033" alt="The book cover of METRO 2033">
                    <figcaption class="font-mono font-bold text-5xl uppercase text-center m-2">METRO 2033</figcaption>
                </figure>
                <img src="arrow" v-show="deviceW < 768">

                <img src="../assets/book_picnic.png" v-show="deviceW > 768" class="h-[350px] w-[250px] opacity-50 hover:opacity-80 hover:cursor-pointer hover:shadow-lg transition-opacity ease-in-out">
            </div>

            <ul class="inline-flex justify-center gap-2 mt-4">
                <li class="w-14 h-14">
                    <img src="../assets/star.png">
                </li>
                <li class="w-14 h-14">
                    <img src="../assets/star.png">
                </li>
                <li class="w-14 h-14">
                    <img src="../assets/star.png">
                </li>
                <li class="w-14 h-14 half">
                    <img src="../assets/star.png">
                </li>
                <li class="w-14 h-14">
                    <img src="../assets/star.png">
                </li>
            </ul>

            <small class="font-bold text-base">5/5</small>

            <div class="bg-amber-600 text-white font-bold mt-2 max-w-[300px] p-2 italic text-lg mb-[50px]">
                <q>Truly a work of art that pushes you to think about the very point of our existence.</q>
            </div>

        </article>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
    data(){
        return{
            deviceW: window.screen.width
        }
    }
});

</script>

<style scoped>
</style>