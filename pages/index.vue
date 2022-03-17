<template>
  <div class="h-full flex flex-col-reverse items-end grid content-end">
    <FurtLogo />
    <div class="w-full flex flex-col grid justify-items-start">
      <img
        class="mx-10 mb-12 w-48"
        src="badges/appstore.svg"
        alt=""
        srcset=""
      />
      <img
        class="mx-10 mb-12 w-48"
        src="badges/playstore.svg"
        alt=""
        srcset=""
      />
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>

<style>
body {
  background-color: #286D4D;
  height: 100vh;
}
#__nuxt {
  height: 100vh;
}
#__layout {
  height: 100vh;
}
</style>
