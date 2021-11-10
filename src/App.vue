<script setup>
  import Navbar from './layouts/Navbar/index.vue'
  import Banner from './layouts/Banner/index.vue'
  import Content from './layouts/Content/index.vue'
</script>

<template>
  <div class="">
    <div class="container pt-20 bg-[#c7d2e4]"></div>
  </div>

  <div class="bg-gradient-to-r from-[#647eac] to-[#9fb1d8] font-tes">
    <div class="container mx-auto pl-20">
      <Navbar />

      <Banner />
    </div>
  </div>

  <div class="bg-[#c7d2e4] pl-20 font-tes">
      <div class="bg-white">
        <div class="container mx-auto flex px-10 py-20">
          <Content />
        </div>
      </div>
  </div>
</template>

<!-- al-isra / abdullah al-mathruud / :17: -->