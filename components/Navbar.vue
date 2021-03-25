<template>
  <div class="w-full flex justify-around py-4 items-center">
    <div class="w-2/12 h-20 pl-10">
      <NuxtLink class="flex items-center" to="/">
        <img class="h-20" src="logo.png" alt="" />
        <div class="pl-4 font-bold text-4xl">DC COMICS</div>
      </NuxtLink>
    </div>
    <div class="w-5/12" />
    <div class="w-5/12 flex justify-around">
      <button class="focus:outline-none text-gray-600 font-bold text-2xl">
        Sobre nosotros
      </button>
      <button class="focus:outline-none text-gray-600 font-bold text-2xl">
        Blog
      </button>
      <button class="focus:outline-none text-gray-600 font-bold text-2xl">
        Contactenos
      </button>
      <button class="focus:outline-none text-gray-600 font-bold text-2xl">
        Publique un trabajo
      </button>
    </div>
  </div>
</template>