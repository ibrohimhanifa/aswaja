<template>
  <div class="bg-gradient-to-br from-green-400 to-green-600 md:overflow-hidden">
    <div class="px-4 py-10 md:py-0">
      <div class="md:max-w-6xl md:mx-auto">
        <div class="md:flex md:flex-wrap">
          <div class="md:w-1/2 text-center md:text-left md:pt-16">
            <h1
              class="font-bold text-white text-2xl md:text-5xl leading-tight mb-4"
            >
              Air mineral paling segar di dunia
            </h1>
            <p class="text-white md:text-xl md:pr-48">
              <span class="font-bold"> Aswaja Yashrab Alma </span>
              merupakan air mineral yang berasal dari sumber mata air pegunungan
              terpilih yang terfilter secara alami dan kaya mineral alami yang
              memberikan kesegaran dan kebaikan pada tubuh kita
            </p>
            <a
              href="https://wa.me/+6287746445826"
              target="_blank"
              class="btn-hero"
              >Pesan Sekarang</a
            >
          </div>
          <div class="md:w-1/2 relative">
            <div class="hidden md:block">
              <img src="~/assets/image/logo1.png" alt="hero" />
            </div>
          </div>
        </div>
      </div>
    </div>
    <svg
      class="fill-current text-white hidden md:block"
      xmlns="http://www.w3.org/2000/svg"
      viewBox="0 0 1440 300"
    >
      <path fill-opacity="1" d="M0,224L1440,32L1440,320L0,320Z"></path>
    </svg>
  </div>
</template>

<style lang="postcss" scoped>
.btn-hero {
  @apply my-6 inline-block py-3 px-8 text-green-500 bg-white font-bold rounded-lg;
  &:md {
    @apply mb-0 mt-10;
  }
  &:hover {
    @apply shadow-2xl transform translate-y-1 scale-110;
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
</style>
