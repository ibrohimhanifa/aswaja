<template>
  <div class="px-4 py-4 md:sticky top-0 z-10">
    <div
      class="md:max-w-6xl md:mx-auto md:flex md:items-center md:justify-between"
    >
      <div class="flex justify-between items-center">
        <nuxt-link to="/" class="py-2 px-4 rounded-lg bg-white">
          <img src="~/assets/image/logo1.png" alt="logo" width="100" />
        </nuxt-link>

        <div
          class="inline-block cursor-pointer md:hidden"
          @click="isOpen = !isOpen"
        >
          <div class="bg-green-500 w-7 my-2" style="height: 2px"></div>
          <div class="bg-green-500 w-7 my-2" style="height: 2px"></div>
          <div class="bg-green-500 w-7 my-2" style="height: 2px"></div>
        </div>
      </div>

      <div
        :class="isOpen ? 'block' : 'hidden'"
        class="px-4 pt-2 pb-4 bg-white rounded-md"
      >
        <nuxt-link to="/" class="nav-menu2">Beranda</nuxt-link>
        <nuxt-link to="/about" class="nav-menu2">Tentang Kami</nuxt-link>
        <nuxt-link to="/contact" class="nav-menu2">Kontak</nuxt-link>
      </div>

      <div>
        <div class="hidden md:block">
          <nuxt-link to="/" class="nav-menu">Beranda</nuxt-link>
          <nuxt-link to="/about" class="nav-menu">Tentang Kami</nuxt-link>
          <nuxt-link to="/contact" class="nav-menu">Kontak</nuxt-link>
        </div>
      </div>

      <!-- <div class="hidden md:block">
            <nuxt-link to="#" class="nav-admin">Admin</nuxt-link>
        </div> -->
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isOpen: false,
    }
  },
}
</script>

<style lang="postcss" scoped>
.nav-admin {
  @apply inline-block py-1 px-4 mx-4 bg-white text-indigo-500 rounded-lg font-bold;
  &:md {
    @apply py-2;
  }
  &:hover {
    @apply text-white bg-indigo-400 rounded-lg shadow-lg;
  }
}

.nav-menu {
  @apply inline-block py-1 px-4 mx-4 bg-white text-green-500 font-bold shadow-lg rounded-lg;
  &:md {
    @apply py-2;
  }
  &:hover {
    @apply text-white bg-green-300 rounded-lg shadow-lg;
  }
  &:focus {
    @apply text-white bg-green-500 rounded-lg;
  }
}

.nav-menu2 {
  @apply mt-1 block px-2 py-1 text-green-500 font-semibold rounded;
  &:hover {
    @apply text-white bg-green-300 rounded-lg;
  }
  &:focus {
    @apply text-white bg-green-500 rounded-lg;
  }
}
</style>
