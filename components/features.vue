<template>
  <div class="pt-16 container px-6">
    <div class="flex">
      <h1
        class="text-4xl leading-none font-extrabold tracking-tight text-gray-900 dark:text-white mt-10 sm:mt-14 mb-10"
      >
        My Projects
      </h1>
    </div>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-x-10 gap-y-16">
      <div
        class="w-full post cursor-pointer"
        v-for="(p, i) in work"
        :key="p.id"
      >
        <nuxt-link :to="`/portfolio/${p.slug}`" class="">
          <div
            class="relative mb-6 h-48 w-full object-cover object-center overflow-hidden rounded-lg"
          >
            <img
              class="absolute h-48 w-full object-cover object-center"
              :src="`https://source.unsplash.com/random?sig=${i}`"
              alt="content"
            />
          </div>
          <h2
            class="text-lg text-gray-900 font-black title-font dark:text-white"
          >
            {{ p.title }}
          </h2>
          <p class="leading-relaxed text-base dark:text-white pt-2">
            {{ p.summary  }}
          </p>
        </nuxt-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  async fetch() {
    this.work = await this.$content(`works`).fetch();
  },
  data() {
    return {
      work: [
        // {
        //   id: 1,
        //   title: "Rennec",
        //   description:
        //     "Fingerstache flexitarian street art 8-bit waistcoat. Distillery hexagon disrupt edison bulbche.",
        //   slug: "rennec",
        // },
        // {
        //   id: 2,
        //   title: "Chichen Itza",
        //   description:
        //     "Fingerstache flexitarian street art 8-bit waistcoat. Distillery hexagon disrupt edison bulbche.",
        //   slug: "abcdef",
        // },
        // {
        //   id: 3,
        //   title: "Chichen Itza",
        //   description:
        //     "Fingerstache flexitarian street art 8-bit waistcoat. Distillery hexagon disrupt edison bulbche.",
        //   slug: "abcdef",
        // },
        // {
        //   id: 4,
        //   title: "Chichen Itza",
        //   description:
        //     "Fingerstache flexitarian street art 8-bit waistcoat. Distillery hexagon disrupt edison bulbche.",
        //   slug: "abcdef",
        // },
        // {
        //   id: 5,
        //   title: "Chichen Itza",
        //   description:
        //     "Fingerstache flexitarian street art 8-bit waistcoat. Distillery hexagon disrupt edison bulbche.",
        //   slug: "abcdef",
        // },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
.post {
  img {
    transition: transform 0.3s ease-out;
  }
  &:hover {
    img {
      transform: scale(1.1);
      transition: transform 0.3s ease-out;
    }
  }
}
</style>
