<template>
  <div class="px-4 py-4 fixed bottom-0 right-0 z-10">
    <div class="block">
      <a href="https://wa.me/+6287746445826" target="_blank" class="nav-menu"
        >Pesan WA</a
      >
    </div>
  </div>
</template>

<script>
export default {}
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
