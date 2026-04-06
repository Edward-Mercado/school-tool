<template>
    <div class="bg-linear-to-tr from-black to-indigo-950">
        <div class="w-full flex items-center h-[13%] rounded-br-2xl rounded-bl-2xl px-[1%]">
            <h1 class="text-white text-center w-full lg:text-left title-font text-5xl"> Edward's <span class="text-cyan-300">Epic</span> Tracker </h1>
        </div>
        <div class="h-2 w-[98%] rounded-full mx-[1%] mb-3 bg-cyan-300 text-cyan-300"></div>
        <slot class="h-[80%]"></slot>
        <div
            class="fixed bottom-0 bg-blue-900/10 border-blue-900/30 w-full flex justify-center items-center h-[13%] rounded-tr-[10%] rounded-tl-[10%] px-[4%]">
            <nav-bar></nav-bar>
        </div>
    </div>
</template>

<script setup lang="ts">

</script>

<style scoped></style>