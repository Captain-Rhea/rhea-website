<script setup lang="ts"></script>

<template>
  <div id="sectionHero">
    <div class="relative aspect-video w-full h-screen p-4 md:p-6">
      <NuxtImg
        src="/images/hero-img-2.jpg"
        alt="Hero Image"
        class="absolute inset-0 w-full h-full object-cover filter grayscale brightness-50"
      />
      <div
        class="absolute inset-0 flex items-center justify-center text-white text-center"
      >
        <div class="max-w-lg">
          <div class="bg-white/10 py-1 px-2 rounded w-fit mx-auto">
            Caption: Lorem ipsum dolor sit amet consectetur
          </div>
          <div class="text-6xl">We Convert Concepts</div>
          <div class="text-6xl">Into Technology</div>
          <p class="mt-4">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Deleniti
            pariatur, ad aliquid iusto facilis illo provident tempore fuga
            tempora, ipsam, cum nostrum animi eaque nesciunt fugit dolores odit
            eveniet quod!
          </p>
          <div class="mt-8">
            <BaseCtaButton>สนใจปรึกษา</BaseCtaButton>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
