<template>
  <div class="flex justify-between items-center bg-white h-14 p-4">
    <NuxtLink to="/" class="font-bold text-sm text-red-600">LOGO</NuxtLink>
    <div class="flex items-center space-x-5">
      <BaseMenu :items="items" />
      <BaseAvatar></BaseAvatar>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          name: 'home',
          to: '/',
          menu: [
            { name: 'World news', to: '/discovery' },
            { name: 'Travel', to: '/test' },
            { name: 'Tecnology', to: '/test' },
            { name: 'City', to: '/test' },
            { name: 'Culture', to: '/test' },
            { name: 'More ...', to: '/test' },
          ],
        },
        {
          name: 'Discovery',
          to: '/place',
        },
        {
          name: 'Photos',
          to: '/test',
        },
        {
          name: 'Contantc',
          to: '/test',
        },
      ],
    }
  },
}
</script>
