<template>
  <div class="container py-24 px-6">
    <div>
      <nuxt-content :document="data" />
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      data: [],
      slug: this.$route.params.slug,
    };
  },
  async fetch() {
    this.data = await this.$content(`works/${this.slug}`).fetch();
  },
};
</script>