<template>
  <Layout>
    <div class="flex flex-col bg-no-repeat bg-cover bg-center bg-fixed h-64 md:h-screen" style="background-image: url(/assets/me.jpg)">
      <div class="flex flex-col bg-green-600 text-white px-5 bg-opacity-75 h-full md:items-center justify-center">
        <div class="text-2xl">
            &gt; i'm <span class="rounded-md px-2 py-1 bg-white text-green-600 font-normal">posalusa24</span>
        </div>
        <div class="md:text-lg mt-5 md:w-1/2 md:text-center">
          i like programming, watching anime, playing the piano and a lot of other things.
          i dislike front-end development.
        </div>
      </div>
    </div>
    <div class="flex flex-col px-5">
      <div class="text-2xl mt-5">
        &gt; random facts about me
      </div>
      <div class="flex justify-around mt-5">
        <div class="flex flex-col justify-center items-center w-32 h-32">
          <i class="text-5xl fas fa-globe-americas"></i>
          <div class="text-lg font-normal mt-3">country:</div>
          <div class="text-lg font-semibold">myanmar</div>
        </div>
        <div class="flex flex-col justify-center items-center w-32 h-32">
          <i class="text-5xl fas fa-graduation-cap"></i>
          <div class="text-lg font-normal mt-3">education:</div>
          <div class="text-lg font-semibold">sophomore</div>
        </div>
      </div>
      <div class="flex justify-around mt-5">
        <div class="flex flex-col justify-center items-center w-32 h-32">
          <i class="text-5xl fas fa-globe-americas"></i>
          <div class="text-lg font-normal mt-3">university:</div>
          <div class="text-lg font-semibold"><a href="https://uit.edu.mm" target="_blank">uit.edu.mm</a></div>
        </div>
        <div class="flex flex-col justify-center items-center w-32 h-32 text-5xl">
          <i class="fas fa-hotel"></i>
          <div class="text-lg font-normal mt-3">hotel:</div>
          <div class="text-lg font-semibold">trivago</div>
        </div>
      </div>
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'me'
  }
}
</script>
