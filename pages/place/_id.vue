<template>
  <div>
    <Hero />
    <section class="max-w-screen-lg mx-auto my-10">
      <div class="mx-10 text-gray-600 space-y-10 md:flex">
        <div
          class="max-w-xs md:border-solid md:border-r-2 md:border-gray-300 md:pr-10"
        >
          <div class="font-bold text-2xl mb-5 text-black">
            Quisque viverra interdum velit?
          </div>
          <p class="text-sm leading-6">
            Lorem ipsum dolor sit amet consectetur adipiscing elit sodales
            primis, mollis viverra conubia ligula inceptos laoreet libero
            tortor, nascetur non habitasse iaculis tempor nec egestas fames
            augue, platea porta integer nostra curae sed arcu. Nec ut diam
            vulputate ante scelerisque ridiculus lobortis orci mi curae
            himenaeos quis, senectus curabitur ullamcorper a porttitor nibh
            fermentum nisi cum morbi aliquam. Vitae pretium vestibulum dui
            gravida in potenti interdum, class rhoncus neque. Ullamcorper
            porttitor non pharetra cursus nisl mollis pellentesque primis
            penatibus platea, dictum himenaeos eget mi bibendum ad molestie
            aliquet curae quis quisque, nunc duis ac at elementum dui integer
            viverra tempus. Lacinia bibendum diam senectus egestas nec molestie
            convallis aenean hac tempus, vivamus purus congue euismod fringilla
            cursus donec est eu blandit platea, feugiat vitae netus orci
            habitant accumsan placerat morbi nostra. Quam fringilla sociis
            suspendisse quis ultricies dis tellus cum, litora aliquet.
          </p>
        </div>
        <div class="md:pl-10">
          <div class="mb-10">
            <div class="flex items-center font-bold text-xl pb-5 text-black">
              <BaseAvatar />
              <div class="pl-2">Jonathan Walker</div>
            </div>
            <p class="text-sm pb-3 leading-6">
              In hac habitasse platea dictumst. Sed nec venenatis odio. Nulla
              faucibus ipsum sed faucibus accumsan. Donec rhoncus luctus massa
              vitae lobortis. Duis consequat, nunc a pretium imperdiet, neque
              est rhoncus massa, tristique rutrum nisl risus at libero.
            </p>
            <div class="text-sm italic">2 min ago</div>
          </div>
          <div class="mb-10">
            <div class="flex items-center font-bold text-xl pb-5 text-black">
              <BaseAvatar />
              <div class="pl-2">Brenda Mercer</div>
            </div>
            <p class="text-sm pb-3 leading-6">
              In hac habitasse platea dictumst. Sed nec venenatis odio. Nulla
              faucibus ipsum sed faucibus accumsan. Donec rhoncus luctus massa
              vitae lobortis. Duis consequat, nunc a pretium imperdiet, neque
              est rhoncus massa, tristique rutrum nisl risus at libero.
            </p>
            <div class="text-sm italic">2 min ago</div>
          </div>
          <iframe
            class="h-64 w-full mb-10 rounded"
            src="https://www.youtube.com/embed/ywuVe6T2P2E"
          >
          </iframe>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {}
</script>
