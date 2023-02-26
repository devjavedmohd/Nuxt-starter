<template>
  <!--  Cars page  -->
  <div class="mx-auto mt-4 max-w-7xl space-y-4 px-4 xs:px-8 sm:px-10 lg:px-16 pb-16 w-full">
    <div class="mt-32 flex">
      <!--   Car side bar   -->
      <div class="shadow border w-64 mr-10 z-30 h-[190px]">
        <div class="p-5 flex justify-between relative cursor-pointer border-b">
          <h3>Location</h3>
          <h3 class="text-blue-400 capitalize">Ottawa</h3>
            <div class="absolute border shadow left-56 p-5 top-1 -m-1 bg-white">
                <input type="text" class="border p-1 rounded">
                <button class="bg-blue-400 w-full py-1 mt-2 rounded text-white">Apply</button>
            </div>
        </div>
        <div class="p-5 flex justify-between relative cursor-pointer border-b">
          <h3 class="bold-600">Make</h3>
          <h3 class="text-blue-400 capitalize">Toyota</h3>
        </div>
        <div class="p-5 flex justify-between relative cursor-pointer border-b">
          <h3 class="bold-600">Price</h3>
          <h3 class="text-blue-400 capitalize">123456</h3>
        </div>
      </div>
      <!--   Car side bar   -->

      <!--   Car side cards   -->
      <div class="w-full">
        <!--    Car Card    -->
        <div class="shadow border w-full overflow-hidden mb-5 cursor-pointer h-[200px]" >
          <div class="flex h-full">
            <img src="https://atcimages.kbb.com/hn/c/341c927518e6477d968c2a7bf89a4167.jpg" alt=""
                 class="w-[300px] h-full" />
            <div class="p-4 flex flex-col">
              <div>
                <h1 class="text-2xl text-blue-700">Audi Car</h1>
                <p class="text-gray-700">lorem ipsum dolor sit amet, consectetur</p>
                <h1 class="mt-auto">$39,555</h1>
              </div>
            </div>
          </div>
        </div>
        <!--    Car Card    -->
      </div>
      <!--   Car side cards   -->
    </div>
  </div>
  <!--  Cars page  -->
</template>

<script>
export default {
name: "Cars"
}
</script>

<style scoped>

</style>