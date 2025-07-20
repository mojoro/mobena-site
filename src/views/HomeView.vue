<script setup lang="ts"></script>

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
      <div class="absolute bottom-8 left-1/2 -translate-x-1/2 transform">
        <div class="animate-pulse-vibrance cursor-pointer text-center">
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
    <div class="feature-section w-full px-4 py-16">
      <div class="mx-auto max-w-7xl text-center">
        <h2 class="text-3xl font-bold tracking-tight text-white sm:text-4xl">
          Changing Tax and Accounting Forever
        </h2>
        <p class="mx-auto mt-4 max-w-2xl text-lg text-white/80">
          Mobena is the first income and estate tax planning platform that provides accurate
          planning over a multigenerational timeframe
        </p>
        <div class="mt-12 grid gap-8 md:grid-cols-3">
          <div class="flex h-96 flex-col rounded-xl bg-[var(--mobena-soft-blue)] p-6 text-left">
            <img
              class="mb-4 h-48 w-full rounded-lg object-cover"
              alt="Accurate Income Tax"
              src="https://cdn.prod.website-files.com/643010cf972169b0d887edac/6706394cb9459aaa57b8ddc4_Teisis6.jpg"
            />
            <h3 class="mb-2 text-xl font-bold text-white">Accurate Income Tax</h3>
            <p class="flex-grow text-white/90">
              Mobena was created by family office tax advisors to model tax the way that CPAs model
              tax for wealthy families
            </p>
          </div>
          <div class="flex h-96 flex-col rounded-xl bg-[var(--mobena-soft-blue)] p-6 text-left">
            <img
              class="mb-4 h-48 w-full rounded-lg object-cover"
              alt="Real Life Structures"
              src="https://apptad.com/wp-content/uploads/2025/04/AdobeStock_473276539-2.jpeg"
            />
            <h3 class="mb-2 text-xl font-bold text-white">Real Life Structures</h3>
            <p class="flex-grow text-white/90">
              Like real life, Mobena reflects tiered-entity structures for the entire family and
              their trusts.
            </p>
          </div>
          <div class="flex h-96 flex-col rounded-xl bg-[var(--mobena-soft-blue)] p-6 text-left">
            <img
              class="mb-4 h-48 w-full rounded-lg object-cover"
              alt="Trust and Estate Models"
              src="https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcSbNO5kx_SPn76j6XQD3GlZjUf4XySpqE5LSlAj6OniEWvuG94w"
            />
            <h3 class="mb-2 text-xl font-bold text-white">Trust and Estate Models</h3>
            <p class="flex-grow text-white/90">
              Mobena was built to handle accurate trust income tax and estate tax treatment.
            </p>
          </div>
        </div>
      </div>
    </div>
    <footer class="w-full p-4 font-roboto text-xs text-white">
      <div class="container mx-auto flex items-center justify-between">
        <p class="text-white/70">© 2025 Mobena Evolution LLC</p>
        <div class="hidden items-center space-x-6 sm:flex"></div>
      </div>
    </footer>
  </div>
</template>

<style scoped></style>
