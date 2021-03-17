<template>
  <div
    class="card p-10 bg-gray-600 flex flex-col justify-between text-white rounded"
    :style="`background-image: url('${bgImg}');background-size: cover;`"
  >
    <div class="text-base font-bold uppercase">Title</div>
    <div>
      <div class="text-2xl font-bold">
        Cras vitae mattis lacus. Integer sit amet.
      </div>
      <p class="text-base">
        Lorem ipsum dolor sit amet, in eam odio amet, vix id nullam detracto,
        vidit vituperatoribus duo id. Affert detraxit voluptatum vis eu, inermis
        eloquentiam.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  computed: {
    bgImg() {
      return require('@/assets/images/card.png')
    },
  },
}
</script>
