<script setup>
import { Icon } from '@iconify/vue'
</script>

<template>
  <main>
    <header class="relative py-[40vh] bg-[url(../assets/ham1.jpeg)] bg-cover bg-no-repeat px-[5%]">
      <!-- Overlay -->
      <div class="absolute inset-0 bg-black opacity-80"></div>

      <!-- Text content -->
      <div class="relative z-10 text-center md:text-left">
        <div class="uppercase mb-4 font-medium text-2xl text-gray-400">The new meta is here</div>
        <h1 class="font-bold text-6xl text-white">HAMTARO</h1>
      </div>
    </header>

    <!-- About Section -->
    <section
      class="grid grid-cols-1 md:grid-cols-2 gap-20 px-[15%] py-20 bg-gradient-to-r from-[#0f172a] via-[#1e3a8a] to-[#17328b]"
    >
      <div class="max-h-[60vh]">
        <img
          src="../assets/ham1.jpeg"
          alt="Hamtaro 1"
          class="w-full aspect-square object-cover rounded-full"
        />
      </div>
      <div class="flex flex-col justify-center gap-4">
        <h2 class="text-3xl font-medium">About</h2>
        <p class="text-lg font-light">
          Hamtaro is the adorable hamster from the late 1980s Japanese Anime and manga, was a global
          hit, especially among Anime lovers and early Internet adopters. Before Animes like Shiba
          Inu(Retro Asian Twist) Domo-Kun, HAMTARO was a legendary hamster icon across the entire
          Asia region in the late 1980s to early 1990s.
        </p>
      </div>
    </section>

    <section class="py-24">
      <h2
        class="w-[90%] md:w-[60%] mx-auto text-3xl md:text-5xl uppercase font-bold text-center md:leading-18"
      >
        $Hamtaro is here to make
        <span class="bg-blue-800">memecoins fun again.</span>
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-20 px-[15%] py-20 items-center">
        <div>
          <div class="flex gap-4 mb-8">
            <div>
              <Icon icon="ri:coins-fill" class="text-5xl text-blue-500" />
            </div>
            <div>
              <h2 class="mb-2 font-bold text-2xl">Token Supply 1B</h2>
              <p class="text-lg">
                No VC games. <br />
                No presale. <br />
                No taxes. <br />
                Contract renounced. LP burnt.
              </p>
            </div>
          </div>
          <div class="flex gap-4 mb-8">
            <div>
              <Icon icon="f7:car-fill" class="text-5xl text-blue-500" />
            </div>
            <div>
              <h2 class="mb-2 font-bold text-2xl">Free to Test Drive</h2>
              <p class="text-lg">“He’s not just a coin. He’s a character. He’s a movement.”</p>
            </div>
          </div>
          <div class="flex gap-4">
            <div>
              <Icon icon="f7:hand-thumbsup-fill" class="text-5xl text-blue-500" />
            </div>
            <div>
              <h2 class="mb-2 font-bold text-2xl">Good Quality</h2>
              <div class="text-lg">
                Backed by pure meme energy, degenerate spirit and a malice you can't help but love,
                Hantaro is the next evolution of crypto culture.
              </div>
            </div>
          </div>
        </div>
        <div>
          <img
            src="../assets/ham2.jpeg"
            alt="Hamtaro 2"
            class="w-full aspect-square object-cover"
          />
        </div>
      </div>
    </section>

    <footer class="mt-16 text-center">
      <div class="flex justify-center gap-2">
        <a href=""><Icon icon="streamline-logos:telegram-logo-2" width="40" height="40" /></a>
        <a href=""><Icon icon="hugeicons:new-twitter-ellipse" width="40" height="40" /></a>
      </div>

      <div class="mt-8 text-sm">© 2025 – Hamtaro</div>
    </footer>
  </main>
</template>
