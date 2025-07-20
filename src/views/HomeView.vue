<script setup lang="ts">
import FeatureSection from '../components/FeatureSection.vue'
function scrollToBottom() {
  window.scrollTo({
    top: document.body.scrollHeight,
    behavior: 'smooth',
  })
}
</script>

<template>
  <div>
    <div class="relative flex min-h-screen w-full flex-col items-center justify-between">
      <div
        class="mx-auto flex w-full max-w-sm flex-col items-center px-4 py-8 sm:max-w-sm sm:py-12 md:max-w-md lg:max-w-2xl"
      >
        <img
          alt="Mobena logo"
          class="h-auto w-4/5 max-w-[200px] sm:max-w-[250px] md:max-w-[300px] lg:max-w-[350px]"
          src="../assets/mobena_logo.png"
        />
        <p
          class="mt-8 text-center font-oxygen text-2xl whitespace-nowrap text-white uppercase sm:mt-4 sm:text-3xl md:mt-4 md:text-4xl lg:mt-4 lg:text-[48px]"
        >
          INTELLIGENT TAX PLANNING
        </p>
        <div class="mt-4 w-full text-center font-poppins sm:mt-4 md:mt-8 lg:mt-12">
          <p
            class="mx-auto px-2 text-xl leading-relaxed font-medium text-white sm:px-0 sm:text-2xl"
          >
            The Mobena financial and tax system will revolutionize tax planning for the wealthiest
            families in the world
          </p>
        </div>
        <div
          class="mx-auto mt-6 flex w-full max-w-sm flex-col items-center px-4 sm:max-w-md md:max-w-lg lg:max-w-2xl"
        >
          <div class="w-full max-w-xl">
            <form class="flex w-full flex-col gap-3 sm:flex-row">
              <input
                id="email"
                placeholder="name@email.com"
                required=""
                class="flex-grow rounded-md border-0 bg-white px-4 py-3 text-sm text-gray-900 placeholder-gray-500 focus:ring-2 focus:ring-blue-300 focus:ring-inset"
                type="email"
                value=""
              /><button
                type="submit"
                class="rounded-md bg-[var(--mobena-soft-blue)] px-6 py-3 text-sm font-semibold text-white transition-all hover:cursor-pointer hover:outline-1 hover:outline-white hover:bg-[var(--mobena-dark-blue)]"
              >
                Submit
              </button>
            </form>
            <p class="mx-auto mt-4 max-w-md text-center text-sm leading-relaxed text-white/80">
              CPAs, family offices and advisors to wealthy families will get updates as our software
              becomes available
            </p>
          </div>
        </div>
      </div>
      <div class="absolute bottom-18 left-1/2 -translate-x-1/2 transform">
        <div class="animate-bounce-down cursor-pointer text-center" @click="scrollToBottom">
          <p class="font-poppins text-lg tracking-wider"></p>
          <svg
            stroke="#ffffff"
            fill="#ffffff"
            stroke-width="0"
            viewBox="0 0 384 512"
            class="mx-auto mt-4 h-6 w-6"
            height="1em"
            width="1em"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M169.4 470.6c12.5 12.5 32.8 12.5 45.3 0l160-160c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0L224 370.8 224 64c0-17.7-14.3-32-32-32s-32 14.3-32 32l0 306.7L54.6 265.4c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3l160 160z"
            ></path>
          </svg>
        </div>
      </div>
    </div>
    <FeatureSection />
    <footer class="w-full p-4 font-roboto text-xs text-white">
      <div class="container mx-auto flex items-center justify-between">
        <p class="text-white/70">© 2025 Mobena Evolution LLC</p>
        <div class="hidden items-center space-x-6 sm:flex"></div>
      </div>
    </footer>
  </div>
</template>

<style scoped>
@keyframes bounce-down {
  0%,
  100% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(18px);
  }
}
.animate-bounce-down {
  animation: bounce-down 2.3s infinite;
}
</style>
