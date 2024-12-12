<script setup lang="ts"></script>

<template>
  <div class="w-full px-4 py-2 bg-white dark:bg-black dark:text-white">
    <div class="container mx-auto">
      <div class="grid grid-cols-12">
        <div class="col-span-2 flex items-center w-full h-full">
          <LogoComponentRhea class="w-[120px] h-auto" />
        </div>
        <div
          class="col-span-8 flex items-center justify-center gap-6 w-full h-full"
        >
          <NuxtLink to="/">Home</NuxtLink>
          <NuxtLink to="/">Services</NuxtLink>
          <NuxtLink to="/">About Us</NuxtLink>
          <NuxtLink to="/">Contact</NuxtLink>
        </div>
        <div
          class="col-span-2 flex items-center justify-end gap-4 w-full h-full"
        >
          <BaseCtaButton>สนใจปรึกษา</BaseCtaButton>
        </div>
      </div>
    </div>
  </div>
</template>
