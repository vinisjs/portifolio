<template lang="">
  <section class="bg-zinc-700 p-2 rounded-md shadow-md">
    <div class="grid grid-cols-1 grid-flow-rows gap-2 max-w-[1fr] max-h-max">
      <img :src="img" alt="img" />
      <h2 class="text-lg font-semibold">{{ title }}</h2>
      <p>{{ description }}</p>
      <nuxt-link
        class="text-center p-2 bg-zinc-600 rounded-lg hover:text-sky-500 hover:bg-zinc-500"
        :to="linkPath"
        >Veja mais
      </nuxt-link>
    </div>
  </section>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      required: true,
    },
    description: {
      type: String,
      required: true,
    },
    img: String,
    // hasLink: Boolean,
    linkPath: String,
  },
};
</script>
