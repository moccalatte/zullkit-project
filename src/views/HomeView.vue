<script setup>
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <main>
    <div class="relative overflow-hidden bg-white">
      <div class="mx-auto max-w-7xl">
        <div
          class="z-10 px-5 pb-8 bg-white xl:pl-20 lg:pl-16 sm:pb-16 md:pb-20 lg:max-w-2xl lg:w-full lg:pb-28 xl:pb-32"
        >
          <main
            class="mx-auto mt-10 max-w-7xl sm:mt-12 md:mt-16 lg:mt-20 xl:mt-36"
          >
            <div class="sm:text-center lg:text-left">
              <h1
                class="text-3xl font-bold leading-normal tracking-tight text-gray-900 sm:text-4xl md:text-5xl"
              >
                <span class="block lg:mb-2">Design Better &</span>
                <span class="block">Faster Than Before.</span>
              </h1>
              <p
                class="mt-3 text-base text-gray-500 sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto md:mt-5 md:text-xl lg:mx-0"
              >
                Accelerate your work with our millions
                <span class="block lg:mb-1"></span> of ready-to-use design projects.
              </p>
              <div
                class="mt-5 sm:mt-8 sm:flex sm:justify-center lg:justify-start"
              >
                <div class="rounded-full">
                  <a
                    href="#"
                    class="flex items-center justify-center w-full px-8 py-3 text-base font-medium text-white bg-indigo-600 border border-transparent rounded-full hover:bg-indigo-700 md:py-2 md:text-lg md:px-10 hover:shadow"
                  >
                    Browse Now
                  </a>
                </div>
              </div>
            </div>
          </main>
        </div>
      </div>
      <div class="lg:absolute lg:inset-y-0 lg:right-0 lg:w-1/2">
        <img class="w-full lg:w-3/4 lg:mt-8" src="@/assets/img/hero-image.png" alt="" />
      </div>
    </div>

    <div class="container px-4 mx-auto my-16 md:px-12">
      <h2 class="mb-4 text-xl font-medium md:mb-0 md:text-lg">Top Categories</h2>
      <div class="flex flex-wrap -mx-1 lg:-mx-4">
        <div class="w-full px-1 my-1 md:w-1/2 lg:my-4 lg:px-4 lg:w-1/4">
          <div class="overflow-hidden border border-gray-200 rounded-xl">
            <a href="details.html">
              <div class="m-4 overflow-hidden rounded-xl">
                <img
                  alt="Placeholder"
                  class="block w-full h-auto"
                  src="@/assets/img/categories-1.jpg"
                />
              </div>
            </a>

            <header
              class="px-4 mb-4 leading-tight"
            >
              <h1 class="text-lg">
                <a class="font-semibold text-black no-underline hover:underline" href="#">
                  Mobile UI Kit
                </a>
              </h1>
              <span class="block text-sm font-light text-gray-500 no-underline">
                731 items
              </span>
            </header>
          </div>
        </div>
        <div class="w-full px-1 my-1 md:w-1/2 lg:my-4 lg:px-4 lg:w-1/4">
          <div class="overflow-hidden border border-gray-200 rounded-xl">
            <a href="details.html">
              <div class="m-4 overflow-hidden rounded-xl">
                <img
                  alt="Placeholder"
                  class="block w-full h-auto"
                  src="@/assets/img/categories-2.jpg"
                />
              </div>
            </a>

            <header
              class="px-4 mb-4 leading-tight"
            >
              <h1 class="text-lg">
                <a class="font-semibold text-black no-underline hover:underline" href="#">
                  Fonts
                </a>
              </h1>
              <span class="block text-sm font-light text-gray-500 no-underline">
                657 items
              </span>
            </header>
          </div>
        </div>
        <div class="w-full px-1 my-1 md:w-1/2 lg:my-4 lg:px-4 lg:w-1/4">
          <div class="overflow-hidden border border-gray-200 rounded-xl">
            <a href="details.html">
              <div class="m-4 overflow-hidden rounded-xl">
                <img
                  alt="Placeholder"
                  class="block w-full h-auto"
                  src="@/assets/img/categories-3.jpg"
                />
              </div>
            </a>

            <header
              class="px-4 mb-4 leading-tight"
            >
              <h1 class="text-lg">
                <a class="font-semibold text-black no-underline hover:underline" href="#">
                  Icon Set
                </a>
              </h1>
              <span class="block text-sm font-light text-gray-500 no-underline">
                83,559 items
              </span>
            </header>
          </div>
        </div>
        <div class="w-full px-1 my-1 md:w-1/2 lg:my-4 lg:px-4 lg:w-1/4">
          <div class="overflow-hidden border border-gray-200 rounded-xl">
            <a href="details.html">
              <div class="m-4 overflow-hidden rounded-xl">
                <img
                  alt="Placeholder"
                  class="block w-full h-auto"
                  src="@/assets/img/categories-4.jpg"
                />
              </div>
            </a>

            <header
              class="px-4 mb-4 leading-tight"
            >
              <h1 class="text-lg">
                <a class="font-semibold text-black no-underline hover:underline" href="#">
                  Website UI Kit
                </a>
              </h1>
              <span class="block text-sm font-light text-gray-500 no-underline">
                4,500 items
              </span>
            </header>
          </div>
        </div>
      </div>
    </div>

    <div class="container px-4 mx-auto my-16 md:px-12">
      <h2 class="mb-4 text-xl font-medium md:mb-0 md:text-lg">New Items</h2>
      <div class="flex flex-wrap -mx-1 lg:-mx-4">
        <div class="w-full px-1 my-1 md:w-1/2 lg:my-4 lg:px-4 lg:w-1/3">
          <div class="overflow-hidden border border-gray-200 rounded-xl">
            <a href="details.html">
              <div class="m-4 overflow-hidden rounded-xl">
                <img
                  alt="Placeholder"
                  class="block w-full h-auto"
                  src="@/assets/img/items-1.jpg"
                />
              </div>
            </a>

            <header
              class="px-4 mb-4 leading-tight"
            >
              <h1 class="text-lg">
                <a class="font-semibold text-black no-underline hover:underline" href="#">
                  Mobile UI Kit
                </a>
              </h1>
              <span class="block text-sm font-light text-gray-500 no-underline">
                Mobile UI Kit
              </span>
            </header>
          </div>
        </div>
        <div class="w-full px-1 my-1 md:w-1/2 lg:my-4 lg:px-4 lg:w-1/3">
          <div class="overflow-hidden border border-gray-200 rounded-xl">
            <a href="details.html">
              <div class="m-4 overflow-hidden rounded-xl">
                <img
                  alt="Placeholder"
                  class="block w-full h-auto"
                  src="@/assets/img/items-2.jpg"
                />
              </div>
            </a>

            <header
              class="px-4 mb-4 leading-tight"
            >
              <h1 class="text-lg">
                <a class="font-semibold text-black no-underline hover:underline" href="#">
                  Online Doctor Consultation
                </a>
              </h1>
              <span class="block text-sm font-light text-gray-500 no-underline">
                Website UI Kit
              </span>
            </header>
          </div>
        </div>
        <div class="w-full px-1 my-1 md:w-1/2 lg:my-4 lg:px-4 lg:w-1/3">
          <div class="overflow-hidden border border-gray-200 rounded-xl">
            <a href="details.html">
              <div class="m-4 overflow-hidden rounded-xl">
                <img
                  alt="Placeholder"
                  class="block w-full h-auto"
                  src="@/assets/img/items-3.jpg"
                />
              </div>
            </a>

            <header
              class="px-4 mb-4 leading-tight"
            >
              <h1 class="text-lg">
                <a class="font-semibold text-black no-underline hover:underline" href="#">
                  Banking Crypto
                </a>
              </h1>
              <span class="block text-sm font-light text-gray-500 no-underline">
                Mobile UI Kit
              </span>
            </header>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>
