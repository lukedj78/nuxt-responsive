<template>
  <div
    class="flex flex-col justify-between text-white p-5 md:p-20 bg-gray-400 h-72"
    :style="`background-image: url('${bgImg}');background-size: cover;`"
  >
    <div class="text-center mt-20">
      <div
        v-appear:top="{ delay: 300, duration: 700 }"
        class="uppercase text-3xl font-bold"
      >
        Amazing place in America to visit
      </div>
      <ul class="flex justify-between m-auto font-bold uppercase text-sm w-64">
        <li v-appear:left="{ delay: 500, duration: 700 }">Travelguide</li>
        <li v-appear:right="{ delay: 500, duration: 700 }">World news</li>
      </ul>
    </div>
    <div class="flex justify-between items-end mt-20">
      <div
        v-appear:left="{ delay: 1000, duration: 700 }"
        class="flex justify-between items-center"
      >
        <BaseAvatar />
        <div class="text-sm pl-4 font-bold hidden md:block">
          by Steven Voorhees
        </div>
      </div>

      <div
        v-appear:right="{ delay: 1000, duration: 700 }"
        class="p-5 rounded border-dashed md:border-2 md:border-white md:max-w-xs"
      >
        <div class="uppercase font-bold text-base text-red-600">Next story</div>
        <div class="font-bold text-sm hidden md:block">
          Morbi eleifend a libero
        </div>
        <p class="text-sm hidden md:block">
          Quisque viverra interdum velit, et cursus magna sagittis in. In dui
          dui.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  computed: {
    bgImg() {
      return require('@/assets/images/hero.png')
    },
  },
}
</script>
