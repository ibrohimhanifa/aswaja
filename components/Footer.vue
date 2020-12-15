<template>
  <footer class="flex justify-center m-10 text-green-500 bg-white">
    <div class="container pt-6">
      <!-- <div>
            <h1 class="my-10 text-center text-lg font-bold lg:text-2xl">
                Mari bersama wujudkan pendidikan yang menyeluruh<br> bagi serluruh rakyat Indonesia
            </h1>
        </div> -->
      <div class="bg-white py-8 w-full">
        <div class="container mx-auto px-8">
          <div class="table w-full">
            <div class="sm:table-cell my-10 pr-5">
              <p class="text-white">.</p>
              <img src="~/assets/image/logo.png" width="200" />
            </div>
            <div class="block sm:table-cell">
              <p class="title-footer">Kontak</p>
              <ul class="list-reset text-xs mb-6">
                <li class="">
                  <p class="list-footer">
                    Jalan Lontar No. 2 RT. 014 / RW. 007 <br />
                    Menteng Atas, Setia Budi <br />
                    Jakarta Selatan <br />
                    DKI Jakarta 12960
                  </p>
                </li>
                <li class="">
                  <p class="list-footer">bimbelmonggo@gmail.com</p>
                </li>
                <li class="">
                  <p class="list-footer">+6281287213766 (Engga)</p>
                </li>
              </ul>
            </div>
            <div class="block sm:table-cell">
              <p class="title-footer">Media Sosial</p>
              <ul class="list-reset text-xs mb-6">
                <li class="">
                  <a
                    href="https://www.youtube.com/channel/UCZvpKwJZ3EQsx5Ngo9ceXMQ/featured"
                    target="_blank"
                    class="link-footer"
                    >Bimbel Monggo (YT)</a
                  >
                </li>
                <li class="">
                  <a
                    href="https://www.instagram.com/bimbel_monggo/"
                    target="_blank"
                    class="link-footer"
                    >Bimbel Monggo (IG)</a
                  >
                </li>
                <li class="">
                  <a
                    href="https://www.instagram.com/scmonggo/"
                    target="_blank"
                    class="link-footer"
                    >Super Camp (IG)</a
                  >
                </li>
                <li class="">
                  <a
                    href="https://www.instagram.com/tamanbacaansmooth/"
                    target="_blank"
                    class="link-footer"
                    >Taman Bacaan Smooth (IG)</a
                  >
                </li>
                <li class="">
                  <a
                    href="https://www.instagram.com/aku_setara/"
                    target="_blank"
                    class="link-footer"
                    >Aku Setara (IG)</a
                  >
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
      <div
        class="flex px-3 m-auto pt-5 border-t text-sm flex-col md:flex-row max-w-6xl"
      >
        <div class="mt-2 text-green-400 flex-auto font-bold text-center">
          © Copyright 2020. All Rights Reserved.
        </div>
      </div>
    </div>
  </footer>
</template>

<style lang="postcss" scoped>
.title-footer {
  @apply uppercase text-green-400 text-sm font-bold;
  &:sm {
    @apply mb-6;
  }
}

.list-footer {
  @apply text-green-400 text-sm mt-2 inline-block mr-2;
  &:sm {
    @apply mb-6 block mr-0;
  }

  /* &:hover {@apply text-green-600 ;} */
}

.link-footer {
  @apply text-green-400 text-sm mt-2 inline-block mr-2;
  &:sm {
    @apply mb-6 block mr-0;
  }
  &:hover {
    @apply text-green-600;
  }
}
</style>
