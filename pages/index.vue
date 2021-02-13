<template>

  <div class="container mx-auto">
    <div class="w-100 h-full bg-blue-400">
      <div class="w-50 p-40 bg-black">
        <h1 class="text-5xl leading-none text-white mb-5">Welcome Nuxter</h1>
        <p class="text-white">You are here because of me</p>
        <button class="bg-red-300 px-10 py-4 text-black-400 font-bold mt-5"><nuxt-link to="/about">Learn More</nuxt-link></button>
      </div>
    </div>
    <div class="blurb bg-pink-400 py-5 flex flex-row items-center justify-around">
      <div class="heading">
        <h1 class="text-3xl leading-none text-white">Let's Start The Jouryney</h1>
      </div>
      <div class="cta">
        <button class="bg-red-300 px-10 py-4 text-black-400 font-bold mt-5"><nuxt-link to="/about">Learn More</nuxt-link></button>
      </div>
    </div>

      <h1 class="text-center text-4xl mb-10 pt-20">Services that you would Love</h1>
      <div class="services flex py-20 space-x-10">
        <div class="service p-2 shadow">
          <img class="w-20 h-20 mx-auto mb-4" src="../assets/images/seo.png" alt="">
          <h3 class="text-center text-2xl mb-2">Frontend Application</h3>
          <p class="text-center text-sm">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Adipisci, qui!</p>
          <button class="mx-auto w-full bg-red-300 px-10 py-4 text-black-400 font-bold mt-5">Learn More</button>

        </div>
        <div class="service p-2 shadow">
          <img class="w-20 h-20 mx-auto mb-4" src="../assets/images/seo.png" alt="">
          <h3 class="text-center text-2xl mb-2">Frontend Application</h3>
          <p class="text-center text-sm">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Adipisci, qui!</p>
          <button class="mx-auto w-full bg-red-300 px-10 py-4 text-black-400 font-bold mt-5">Learn More</button>

        </div>
        <div class="service p-2 shadow">
          <img class="w-20 h-20 mx-auto mb-4" src="../assets/images/seo.png" alt="">
          <h3 class="text-center text-2xl mb-2">Frontend Application</h3>
          <p class="text-center text-sm">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Adipisci, qui!</p>
          <button class="mx-auto w-full bg-red-300 px-10 py-4 text-black-400 font-bold mt-5">Learn More</button>

        </div>
      </div>

      <div class="close-stmt p-20 bg-pink-100 text-center shadow-md">
        <h1 class="text-5xl leading-0 font-black">Lets start work</h1>
        <button class="mx-auto bg-red-300 px-10 py-4 text-black-400 font-bold mt-5"><nuxt-link to="/contact">Get Started</nuxt-link></button>
      </div>

      <div class="cta h-3 my-10">
        <h1 class="text-center">Copyright &copy; Shakil Ahmed</h1>
      </div>

    </div>

</template>

<script>
export default {}
</script>

<style>
.page-enter-active,
.page-leave-active {
  transition: opacity 0.5s;
}
.page-enter,
.page-leave-to {
  opacity: 0;
}

.layout-enter-active,
.layout-leave-active {
  transition: opacity 0.5s;
}
.layout-enter,
.layout-leave-to {
  opacity: 0;
}

.slide-bottom-enter-active,
.slide-bottom-leave-active {
  transition: opacity 0.25s ease-in-out, transform 0.25s ease-in-out;
}
.slide-bottom-enter,
.slide-bottom-leave-to {
  opacity: 0;
  transform: translate3d(0, 15px, 0);
}
.bounce-enter-active {
  transform-origin: top;
  animation: bounce-in 0.8s;
}
.bounce-leave-active {
  transform-origin: top;
  animation: bounce-out 0.5s;
}
@keyframes bounce-in {
  0% {
    transform: scale(0);
  }
  50% {
    transform: scale(1.25);
  }
  100% {
    transform: scale(1);
  }
}
@keyframes bounce-out {
  0% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.25);
  }
  100% {
    transform: scale(0);
  }
}
</style>
