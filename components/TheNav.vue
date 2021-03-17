<template>
  <div class="flex justify-between items-center bg-white h-14 p-4">
    <NuxtLink to="/" class="font-bold text-sm text-red-600">LOGO</NuxtLink>
    <div class="flex items-center space-x-5">
      <ul
        class="flex justify-between h-full space-x-5 text-xs text-gray-500 font-bold uppercase cursor-pointer hidden md:flex"
      >
        <NuxtLink to="/" class="text-black relative">
          <div>Home</div>
          <ul
            class="mt-5 p-4 text-gray-500 bg-white absolute w-40 rounded space-y-3 hidden"
          >
            <li>World news</li>
            <li>Travel</li>
            <li class="text-black">Tecnology</li>
            <li>City</li>
            <li>Culture</li>
            <li>More ...</li>
          </ul>
        </NuxtLink>
        <NuxtLink to="/">Discovery</NuxtLink>
        <NuxtLink to="/">Photos</NuxtLink>
        <NuxtLink to="/">Contact</NuxtLink>
      </ul>
      <BaseAvatar></BaseAvatar>
    </div>
  </div>
</template>

<script>
export default {}
</script>
