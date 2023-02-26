<template>
  <div>
    <NavBar />
    <div class="mx-auto mt-4 max-w-7xl space-y-4 px-4 xs:px-8 sm:px-10 lg:px-16 pb-16 w-full">
      <div>
        <div class="mt-10">
          <img alt="" src="https://atcimages.kbb.com/hn/c/341c927518e6477d968c2a7bf89a4167.jpg"
               class="w-full" />
          <h1 class="mt-10 text-4xl">Audi</h1>
          <div class="text-slate-500 flex text-lg mt-3 border-b py-5 justify-between items-center">
            <div class="flex">
              <p class="mr-2">5 seats</p>
              <p class="mr-2">|</p>
              <p class="mr-2">67,000 miles</p>
            </div>
            <div>
              <p class="font-bold text-2xl">$35,000</p>
            </div>
          </div>
        </div>
      </div>
      <div class="mr-10 mt-5 border-b pb-5">
        <div class="flex text-lg mt-2">
          <p class="rounded text-lime-800 mr-3">✔️</p>
          <p>Leather Interior</p>
        </div>
      </div>
      <div class="mt-5">
        <div class="mt-10">
          lorem ipsum content
        </div>
      </div>
      <div class="mt-10">
        <div class="flex w-[600px] justify-between" >
          <input type="text" class="border p-1" placeholder="Name" />
          <input type="text" class="border p-1" placeholder="Email" />
          <input type="text" class="border p-1" placeholder="Phone" />
        </div>
        <div class="flex mt-4 w-[600px]" >
          <textarea class="border p-1 w-full" placeholder="Message"></textarea>
        </div>
        <button class="bg-blue-500 text-white px-10 py-3 rounded mt-4">Submit</button>
      </div>
    </div>
  </div>
</template>

<script>
</script>

<style scoped>

</style>