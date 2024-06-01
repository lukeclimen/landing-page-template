<template>
  <section class="overflow-hidden pt-8 sm:pt-12 lg:relative lg:py-48">
    <div
      class="mx-auto max-w-md px-6 sm:max-w-3xl lg:grid lg:max-w-7xl lg:grid-cols-2 lg:gap-24 lg:px-8"
    >
      <div>
        <div class="mt-20">
          <div class="mt-6 sm:max-w-xl page-header">
            <h1
              class="text-4xl font-bold tracking-tight text-gray-900 sm:text-5xl"
            >
              <ContentSlot :use="$slots.title" />
            </h1>
            <h3 class="mt-6 text-2xl text-gray-500 font-semibold">
              <ContentSlot :use="$slots.subtitle" />
            </h3>
            <p class="mt-12 text-xl text-gray-500">
              <ContentSlot :use="$slots.aboveFormContent" />
            </p>
          </div>
          <form action="#" class="mt-6 sm:flex sm:w-full sm:max-w-lg">
            <div class="min-w-0 flex-1">
              <label for="hero-email" class="sr-only">Email address</label>
              <input
                id="hero-email"
                type="email"
                class="block w-full rounded-md border border-gray-300 px-5 py-3 text-base text-gray-900 placeholder-gray-500 shadow-sm focus:border-rose-500 focus:ring-rose-500"
                placeholder="Enter your email"
              />
            </div>
            <div class="mt-4 sm:ml-3 sm:mt-0">
              <button
                type="submit"
                class="block w-full rounded-md border border-transparent bg-rose-500 px-5 py-3 text-base font-medium text-white shadow hover:bg-rose-600 focus:outline-none focus:ring-2 focus:ring-rose-500 focus:ring-offset-2 sm:px-10"
              >
                <ContentSlot :use="$slots.formButtonContent" />
              </button>
            </div>
          </form>
          <div class="min-w-0 flex-1 py-1 pl-5 text-sm text-gray-500 sm:py-3">
            <p class="font-normal text-gray-600">
              <ContentSlot :use="$slots.belowFormContent" />
            </p>
          </div>
        </div>
      </div>
    </div>

    <div class="sm:mx-auto sm:max-w-3xl sm:px-6">
      <div
        class="py-12 sm:relative sm:mt-12 sm:py-16 lg:absolute lg:inset-y-0 lg:right-0 lg:w-1/2"
      >
        <div class="hidden sm:block">
          <div
            class="absolute inset-y-0 left-1/2 w-screen rounded-l-3xl bg-gray-50 lg:left-80 lg:right-0 lg:w-full"
          />
          <svg
            class="absolute right-1/2 top-8 -mr-3 lg:left-0 lg:m-0"
            width="404"
            height="392"
            fill="none"
            viewBox="0 0 404 392"
          >
            <defs>
              <pattern
                id="837c3e70-6c3a-44e6-8854-cc48c737b659"
                x="0"
                y="0"
                width="20"
                height="20"
                patternUnits="userSpaceOnUse"
              >
                <rect
                  x="0"
                  y="0"
                  width="4"
                  height="4"
                  class="text-gray-200"
                  fill="currentColor"
                />
              </pattern>
            </defs>
            <rect
              width="404"
              height="392"
              fill="url(#837c3e70-6c3a-44e6-8854-cc48c737b659)"
            />
          </svg>
        </div>
        <div
          class="relative -mr-40 pl-6 sm:mx-auto sm:max-w-3xl sm:px-0 lg:h-full lg:max-w-none lg:pl-12"
        >
          <NuxtImg
            class="w-full rounded-md shadow-xl ring-1 ring-black ring-opacity-5 lg:h-full lg:w-auto lg:max-w-none"
            src="https://tailwindui.com/img/component-images/task-app-rose.jpg"
            alt=""
          />
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
import { ChevronRightIcon, StarIcon } from "@heroicons/vue/20/solid";
</script>

<style scoped></style>
