<template>
  <div class="hidden md:flex">
    <ul
      class="flex justify-between h-full space-x-8 text-xs text-gray-500 font-bold uppercase cursor-pointer"
    >
      <li v-for="item in items" :key="item.name">
        <BaseMenuItem :item="item" />
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  props: {
    items: {
      type: Array,
      default() {
        return []
      },
    },
  },
}
</script>
