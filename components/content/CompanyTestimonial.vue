<template>
  <section class="relative sm:py-16 lg:py-0">
    <div
      aria-hidden="true"
      class="hidden sm:block lg:absolute lg:inset-y-0 lg:right-0 lg:w-screen"
    >
      <div
        class="absolute inset-y-0 right-1/2 w-full rounded-r-3xl bg-gray-50 lg:right-72"
      />
      <svg
        class="absolute left-1/2 top-8 -ml-3 lg:-right-8 lg:left-auto lg:top-12"
        width="404"
        height="392"
        fill="none"
        viewBox="0 0 404 392"
      >
        <defs>
          <pattern
            id="02f20b47-fd69-4224-a62a-4c9de5c763f7"
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
          fill="url(#02f20b47-fd69-4224-a62a-4c9de5c763f7)"
        />
      </svg>
    </div>
    <div
      class="relative mx-auto max-w-md px-6 sm:max-w-3xl lg:max-w-none lg:px-0 lg:py-20"
    >
      <!-- Testimonial card-->
      <div class="relative overflow-hidden rounded-2xl pb-10 pt-64 shadow-xl">
        <img
          class="absolute inset-0 h-full w-full object-cover"
          src="https://images.unsplash.com/photo-1521510895919-46920266ddb3?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&fp-x=0.5&fp-y=0.6&fp-z=3&width=1440&height=1440&sat=-100"
          alt=""
        />
        <div class="absolute inset-0 bg-rose-500 mix-blend-multiply" />
        <div
          class="absolute inset-0 bg-gradient-to-t from-rose-600 via-rose-600 opacity-90"
        />
        <div class="relative px-8">
          <div>
            <img
              class="h-12"
              src="https://tailwindui.com/img/logos/workcation.svg?color=white"
              alt="Workcation"
            />
          </div>
          <blockquote class="mt-8">
            <div class="relative text-lg font-medium text-white md:flex-grow">
              <svg
                class="absolute left-0 top-0 h-8 w-8 -translate-x-3 -translate-y-2 transform text-rose-400"
                fill="currentColor"
                viewBox="0 0 32 32"
                aria-hidden="true"
              >
                <path
                  d="M9.352 4C4.456 7.456 1 13.12 1 19.36c0 5.088 3.072 8.064 6.624 8.064 3.36 0 5.856-2.688 5.856-5.856 0-3.168-2.208-5.472-5.088-5.472-.576 0-1.344.096-1.536.192.48-3.264 3.552-7.104 6.624-9.024L9.352 4zm16.512 0c-4.8 3.456-8.256 9.12-8.256 15.36 0 5.088 3.072 8.064 6.624 8.064 3.264 0 5.856-2.688 5.856-5.856 0-3.168-2.304-5.472-5.184-5.472-.576 0-1.248.096-1.44.192.48-3.264 3.456-7.104 6.528-9.024L25.864 4z"
                />
              </svg>
              <p class="relative">
                Tincidunt integer commodo, cursus etiam aliquam neque, et.
                Consectetur pretium in volutpat, diam. Montes, magna cursus
                nulla feugiat dignissim id lobortis amet.
              </p>
            </div>

            <footer class="mt-4">
              <p class="text-base font-semibold text-rose-200">
                Sarah Williams, CEO at Workcation
              </p>
            </footer>
          </blockquote>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts"></script>

<style scoped></style>
