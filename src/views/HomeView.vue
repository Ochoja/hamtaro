<template>
  <main>
    <header class="relative py-[40vh] bg-[url(../assets/ham1.jpeg)] bg-cover bg-no-repeat px-[5%]">
      <!-- Overlay -->
      <div class="absolute inset-0 bg-black opacity-80"></div>

      <!-- Text content -->
      <div class="relative z-10">
        <div class="uppercase mb-4 font-medium text-2xl text-gray-400">The new meta is here</div>
        <h1 class="font-bold text-6xl text-white">HAMTARO</h1>
      </div>
    </header>

    <!-- About Section -->
    <section
      class="grid grid-cols-2 gap-20 px-[15%] py-16 bg-gradient-to-r from-[#0f172a] via-[#1e3a8a] to-[#17328b]"
    >
      <div class="max-h-[60vh]">
        <img
          src="../assets/ham1.jpeg"
          alt=""
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
  </main>
</template>
