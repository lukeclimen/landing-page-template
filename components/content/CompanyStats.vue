<template>
  <section class="mt-10">
    <dl class="grid grid-cols-2 gap-x-4 gap-y-8">
      <div
        v-for="stat in stats"
        :key="stat.label"
        class="border-t-2 border-gray-100 pt-6"
      >
        <dt class="text-base font-medium text-gray-500">
          {{ stat.label }}
        </dt>
        <dd class="text-3xl font-bold tracking-tight text-gray-900">
          {{ stat.value }}
        </dd>
      </div>
    </dl>
    <div class="mt-10">
      <a href="#" class="text-base font-medium text-rose-500"
        >Learn more about how we're changing the world &rarr;</a
      >
    </div>
  </section>
</template>

<script setup lang="ts">
const stats = [
  { label: "Founded", value: "2021" },
  { label: "Employees", value: "5" },
  { label: "Beta Users", value: "521" },
  { label: "Raised", value: "$25M" },
];
</script>

<style scoped></style>
