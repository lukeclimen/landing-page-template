<template>
  <div class="relative mt-20">
    <div
      class="lg:mx-auto lg:grid lg:max-w-7xl lg:grid-cols-2 lg:items-start lg:gap-24 lg:px-8"
    >
      <slot />
      <div class="relative mx-auto max-w-md px-6 sm:max-w-3xl lg:px-0">
        <slot />
      </div>
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped></style>
