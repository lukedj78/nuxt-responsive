<template>
  <div
    class="p-10 md:p-20 lg:py-20 lg:px-40 bg-gray-600 text-white space-y-5 h-full flex flex-col justify-center"
    :style="`background-image: url('${bgImg}');background-size: cover;`"
  >
    <div class="border-b-2 border-white">
      <div class="uppercase text-3xl font-bold mb-5">World News</div>
    </div>
    <div class="font-bold text-xl">Amazing places in America to visit.</div>
    <p class="leading-7">
      For some reason — this country, this city, this neighborhood, this
      particular street — is the place you are living a majority of your life
      in.
    </p>
    <div>
      <button class="btn bg-red-500 mt-5">Learn More</button>
    </div>
  </div>
</template>

<script>
export default {
  computed: {
    bgImg() {
      return require('@/assets/images/home.png')
    },
  },
}
</script>
