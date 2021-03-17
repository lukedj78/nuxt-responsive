<template>
  <div>
    <section class="grid grid-cols-1 lg:grid-cols-5">
      <Jumbotron class="col-span-3" />
      <CardNews class="col-span-2" />
    </section>
    <div class="mx-5 md:mx-10">
      <section class="max-w-screen-lg mx-auto my-20">
        <div>
          <div class="flex justify-between">
            <h2 class="font-bold text-2xl uppercase mb-10">Trending</h2>
            <div></div>
          </div>
          <Slider />
        </div>
        <div></div>
      </section>
      <section class="max-w-screen-lg mx-auto my-20">
        <div class="flex justify-between">
          <h2 class="font-bold text-2xl uppercase mb-10">Happeing now</h2>
          <div></div>
        </div>
        <div
          class="grid grid-cols-1 grid-rows-2 gap-0 md:gap-0 lg:grid-rows-1 lg:grid-cols-3 lg:gap-8"
        >
          <div class="grid grid-cols-1 grid-rows-2 gap-8 col-span-2">
            <Card />
            <Card />
          </div>
          <div
            class="grid md:grid-cols-2 md:grid-rows-2 md:gap-8 lg:grid-cols-1"
          >
            <CardSmall />
            <CardSmall />
            <CardSmall />
          </div>
        </div>
      </section>
    </div>
  </div>
</template>

<script>
export default {}
</script>
