<template>
  <div>
    <div class="relative h-screen w-100 bg-no-repeat bg-cover bg-bottom bg-[url('https://www.hyundai.com/content/dam/hyundai/in/en/data/find-a-car/Verna/Highlights/pc/newvernainnerkv-pc_2.jpg')]">
      <div class="z-10 absolute w-full h-full flex justify-center items-center">
        <div class="text-center w-1/2">
          <h1 class="text-5xl font-serif mb-10 text-white shadow-md">Find your drive</h1>
          <CarSearchBar />
        </div>
      </div>
      <div class="z-1 absolute w-full h-full bg-black opacity-50"></div>
    </div>
  </div>
</template>

<script>

export default {
name: "CarHero",
  components: {  }
}
</script>

<style scoped>

</style>