<template>
  <div
    class="w-full bg-white rounded-xl px-4 py-10 divide-y-4 divide-yellow-600"
  >
    <div class="flex items-center pb-6">
      <img class="w-14 h-14" src="empress.png" alt="" />
      <div class="pl-4">
        <div class="font-semibold text-2xl">
          <slot name="name"></slot>
        </div>
      </div>
      <div class="flex w-full justify-end">
        <button
          v-if="owner"
          class="bg-red-500 font-bold text-xl px-4 py-2 rounded-xl text-white focus:outline-none"
        >
          Eliminar
        </button>
      </div>
    </div>
    <div class="pt-8 px-10">
      <div class="font-bold text-2xl">
        <slot name="date"></slot>
      </div>
      <div class="text-xl pt-4">
        <slot></slot>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    owner: { type: Boolean, default: false },
  },
};
</script>