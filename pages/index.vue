<template>
  <div class="bg-white py-4">
    <main>
      <PageHero />
      <div class="relative mt-20">
        <div
          class="lg:mx-auto lg:grid lg:max-w-7xl lg:grid-cols-2 lg:items-start lg:gap-24 lg:px-8"
        >
          <CompanyTestimonial />
          <div class="relative mx-auto max-w-md px-6 sm:max-w-3xl lg:px-0">
            <CompanyDescription />
          </div>
        </div>
      </div>
      <CallToAction />
    </main>
  </div>
</template>

<script setup>
import { ChevronRightIcon, StarIcon } from "@heroicons/vue/20/solid";
</script>

<style scoped></style>
