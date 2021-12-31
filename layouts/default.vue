<template>
  <div>
    <Header />
    <Nuxt />
    <Footer />
  </div>
</template>

<script>
export default {
  // colorMode: "dark",
  mounted() {
    if (!("theme" in localStorage)) {
      localStorage.theme = "dark";
      this.$colorMode.preference = "dark";
    } else {
      this.$colorMode.preference = localStorage.getItem("theme");
    }
  },
};
</script>

<style lang="scss">
html {
  font-family: "Inter", sans-serif;
  font-weight: 400;
  font-size: 14px;
  word-spacing: 1px;
  // color: map-get($color, secondary);
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  // scroll-behavior: smooth;
}

.manrope {
  font-family: "manrope";
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
  -webkit-tap-highlight-color: transparent;
}

body {
  // background: map-get($color, bg-default);
  background-color: white;
}


.dark body {
  background-color: #000000;
  color: #ebf4f1;
}

::-webkit-scrollbar {
  width: 10px;
}

::-webkit-scrollbar-track {
  -webkit-box-shadow: inset 0 0 2px rgba(0, 0, 0, 0.3);
  border-radius: 10px;
}

::-webkit-scrollbar-thumb {
  border-radius: 10px;
  -webkit-box-shadow: inset 0 0 2px rgba(0, 0, 0, 0.5);
}

.container {
  @apply w-full relative relative max-w-screen-lg mx-auto;
}

.hover {
  transition: all 0.2s ease-in-out;
  @apply box-content p-2 rounded-full;
  &:hover {
    @apply p-2 bg-gray-100 dark:bg-gray-900;
  }
}

.nuxt-content-editor{
  @apply dark:text-black
}

.nuxt-content{
  h1{
    @apply text-6xl font-bold
  }
  h2{
    @apply py-4 text-xl
  }
}
</style>