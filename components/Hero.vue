<template>
  <div
    class="flex flex-col justify-between text-white p-20 bg-gray-400 h-72"
    :style="`background-image: url('${bgImg}');background-size: cover;`"
  >
    <div class="text-center mt-20">
      <div class="uppercase text-3xl font-bold">
        Amazing place in America to visit
      </div>
      <ul class="flex justify-between m-auto font-bold uppercase text-sm w-64">
        <li>Travelguide</li>
        <li>World news</li>
      </ul>
    </div>
    <div class="flex justify-between items-end mt-20">
      <div class="flex justify-between items-center">
        <BaseAvatar />
        <div class="text-sm pl-4 font-bold">by Steven Voorhees</div>
      </div>

      <div class="border-dashed rounded border-2 border-white p-5 w-64">
        <div class="uppercase font-bold text-base text-red-600">Next story</div>
        <div class="font-bold text-sm">Morbi eleifend a libero</div>
        <p class="text-sm">
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
