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
.nav-menu {
  @apply inline-block py-2 px-4 m-4 bg-white text-green-500 font-bold shadow-lg rounded-lg;
  &:hover {
    @apply text-white bg-green-300 rounded-lg shadow-lg;
  }
  &:focus {
    @apply text-white bg-green-500 rounded-lg;
  }
}
</style>
