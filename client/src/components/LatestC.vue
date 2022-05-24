<template>
    <div class="flex justify-center items-center flex-col bg-[rgb(255,250,241)]">
        <div class="flex justify-center items-center flex-col max-w-[1000px]">
            <h3 class="font-tahoma text-5xl mt-8 font-bold text-slate-800">Bringing the latest titles that are worth reading full</h3>

            <div class="flex justify-center items-center flex-row gap-8 mt-6 pb-8 border-b-4 border-amber-500 border-opacity-50">
                <img src="../assets/arrow.png" class="w-14 h-14 rotate-[180deg]">
                <img src="../assets/book_taipan.jpg" class="w-[200px] h-[300px] opacity-60">
                <img src="../assets/book_metro.jpg" class="w-[240px] h-[340px]">
                <img src="../assets/book_picnic.png" class="w-[200px] h-[300px] opacity-60">
                <img src="../assets/arrow.png" class="w-14 h-14">
            </div>

            <h4 class="font-tahoma text-4xl font-bold text-slate-900">METRO 2033</h4>
        </div>

        <div class="text-left max-w-[800px] pb-8">
            <span class="flex flex-row gap-4 mt-4">
                <h5 class="text-left font-tahoma font-bold text-xl pb-8">Rating: </h5>
                <img src="../assets/star.png" class="w-6 h-6">
                <img src="../assets/star.png" class="w-6 h-6">
                <img src="../assets/star.png" class="w-6 h-6">
                <img src="../assets/star.png" class="w-6 h-6">
                <img src="../assets/star.png" class="w-6 h-6">
            </span>

            <q class="font-tahoma font-bold text-2xl italic">A book that changes the course of life for the many wanderers of the metro that we call life</q>

        </div>

    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
    data(){
        return{
        }
    }
});

</script>

<style scoped>
</style>