<template>
  <div class="w-full bg-gray-300 h-screen p-20 flex">
    <div class="w-8/12 px-4 space-y-8">
      <Post>
        <template #name> Carlos Miguel Guzmán </template>
        <template #date> 22/12/2021 </template>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam reiciendis
        placeat voluptas mollitia vitae, excepturi quasi sit cupiditate, vero,
        sequi soluta laudantium nobis blanditiis ex accusamus eveniet nihil iste
        necessitatibus illo eos. Similique corrupti aliquam est voluptate
        aliquid ducimus molestiae sapiente doloremque saepe nobis reprehenderit,
        neque mollitia dolor esse. Nulla?
      </Post>
      <Post>
        <template #name> Carlos Miguel Guzmán </template>
        <template #date> 22/12/2021 </template>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam reiciendis
        placeat voluptas mollitia vitae, excepturi quasi sit cupiditate, vero,
        sequi soluta laudantium nobis blanditiis ex accusamus eveniet nihil iste
        necessitatibus illo eos. Similique corrupti aliquam est voluptate
        aliquid ducimus molestiae sapiente doloremque saepe nobis reprehenderit,
        neque mollitia dolor esse. Nulla?
      </Post>
      <Post>
        <template #name> Carlos Miguel Guzmán </template>
        <template #date> 22/12/2021 </template>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam reiciendis
        placeat voluptas mollitia vitae, excepturi quasi sit cupiditate, vero,
        sequi soluta laudantium nobis blanditiis ex accusamus eveniet nihil iste
        necessitatibus illo eos. Similique corrupti aliquam est voluptate
        aliquid ducimus molestiae sapiente doloremque saepe nobis reprehenderit,
        neque mollitia dolor esse. Nulla?
      </Post>
    </div>
    <div class="w-4/12 px-4">
      <form action="" class="w-full bg-white rounded-xl p-4">
        <label for="">Nombre:</label>
        <input
          class="w-full px-4 border-4 border-blue-400 rounded-xl focus:outline-none py-2 mb-10"
          type="text"
        />
        <label for="" cla>Texto:</label>
        <textarea
          class="w-full px-4 py-2 border-4 border-blue-400 rounded-xl focus:outline-none"
          rows="10"
        ></textarea>
        <div class="text-center mt-6">
          <button
            class="bg-blue-500 py-2 px-6 text-2xl font-semibold rounded-xl focus:outline-none"
          >
            Publicar
          </button>
        </div>
      </form>
    </div>
  </div>
</template>