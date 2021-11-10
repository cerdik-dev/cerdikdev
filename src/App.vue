<script setup lang="ts">

</script>

<template>
  <div id="root-class">
    <section class="profile">
      <img class="avatar" />
      <p class="title">Hadi Purwanto</p>
    </section>
    <section class="about-me">
      <p class="pt-5">I Am TypeScript Or JavaScript Enginer And Graphic Designer</p>
      <p>I Often Use:</p>
      <p>Library Or Framework: React - Vue - Express - TinyHttp</p>
      <p>RunTime JS or Ts : Deno - NodeJs</p>
      <p class="pb-5">Tools-Graphic: Inkscape</p>
    </section>
  </div>
</template>
<style lang="sass" scoped>

#root-class
  @apply h-screen w-screen bg-green-400/35 pt-10 flex flex-col gap-y-6
  & .profile
    @apply w-[80%] bg-red-300 mx-auto flex flex-col gap-y-3 justify-center items-center px-5 py-5 rounded-lg
    & .avatar
      @apply w-36 h-36 rounded-full border border-black
    & .title
      @apply text-2xl text-blue-600
  & .about-me
    @apply mx-auto w-[80%] bg-black/35 rounded-lg border border-red-600 flex flex-col items-center px-5 py3 gap-x-8
</style>