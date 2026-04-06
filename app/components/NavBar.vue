<template>
    <div class="h-full w-full flex justify-between items-center p-[2%]">
        <router-link to="/"
            class="btn h-17 rounded-2xl aspect-square bg-slate-950 border-slate-900 text-slate-800 active:text-cyan-200 active:border-cyan-200 hover:border-cyan-500 hover:text-cyan-500 border-5 py-0.5 flex items-center justify-center">
            <svg class="w-full h-full" xmlns="http://www.w3.org/2000/svg" width="24" height="24"
                viewBox="-25 -30 240 200" fill="none" stroke="currentColor" stroke-width="30" stroke-linecap="round"
                stroke-linejoin="round">
                <polyline points="-20,48 85,-20 190,48" />
                <path d="M5,48 L5,148 Q5,155 12,155 L158,155 Q165,155 165,148 L165,48" />
                <path d="M60,155 L60,110 Q60,100 70,100 L100,100 Q110,100 110,110 L110,155" stroke-width="10" />
            </svg>
        </router-link>

        <router-link to="/schedule-maker"
            class="btn h-17 rounded-2xl aspect:4/3 lg:aspect-2/1 bg-slate-950 border-slate-900 text-slate-800 active:text-cyan-200 active:border-cyan-200 hover:border-cyan-500 hover:text-cyan-500 border-5 py-0.5 flex items-center justify-center">
            <h2 class="font-extrabold subtitle-font"> Schedule Maker </h2>
        </router-link>

        <router-link to="/grade-tracker"
            class="btn h-17 rounded-2xl aspect:4/3 lg:aspect-2/1 bg-slate-950 border-slate-900 text-slate-800 active:text-cyan-200 active:border-cyan-200 hover:border-cyan-500 hover:text-cyan-500 border-5 py-0.5 flex items-center justify-center">
            <h2 class="font-extrabold subtitle-font"> Grade Tracker </h2>
        </router-link>

        <router-link to="/grade-calculator"
            class="btn h-17 rounded-2xl aspect:4/3 lg:aspect-2/1 bg-slate-950 border-slate-900 text-slate-800 active:text-cyan-200 active:border-cyan-200 hover:border-cyan-500 hover:text-cyan-500 border-5 py-0.5 flex items-center justify-center">
            <h2 class="font-extrabold subtitle-font"> Grade Calculator </h2>
        </router-link>
        
    </div>
</template>

<script setup lang="ts">
</script>

<style scoped></style>