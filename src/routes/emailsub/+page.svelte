<script>
  import HomeLink from "$lib/HomeLink.svelte"
  import greenBG from "$lib/assets/bg02.webp"
</script>

<HomeLink />
<!-- BG Container -->
<div class="min-h-screen flex justify-center items-center">
  <!-- Card -->
  <div class="p-2 mx-6 bg-slate-700 rounded-2xl shadow-xl shadow-black/50">
    <!-- flex container -->
    <div class="flex flex-col md:flex-row rounded-l-xl">
      <!-- Image -->
      <img
        src={greenBG}
        alt=""
        class=" object-cover object-top rounded-xl md:rounded-l-xl md:rounded-r-none h-80 md:h-96 transform hover:scale-105 hover:rounded-xl duration-200" />
      <!-- Content -->
      <div class="p-6 md:p-12">
        <h1 class="font-light text-2xl text-center text-white md:text-left">
          Find the Perfect Plant
        </h1>
        <p class="max-w-xs my-4 text-sm text-slate-300">
          Araucaria heterophylla species of conifer. The tree is native to
          Norfolk Island, an Australian overseas territory in the Pacific Ocean
          between New Zealand and New Caledonia, as suggested by its common name
          Norfolk Island pine.
        </p>
        <!-- Email Submit -->
        <div
          class="flex flex-col md:flex-row mt-5 space-y-4 md:space-x-3 md:space-y-0">
          <input
            type="text"
            placeholder="Enter your email address"
            class="flex-grow px-2 py-3 bg-slate-800 text-slate-50 border-none outline-none rounded-md text-center" />
          <button
            class="bg-emerald-600 rounded-md px-5 py-3 text-sm hover:bg-emerald-700 duration-300"
            >Subscribe
          </button>
        </div>
      </div>
    </div>
  </div>
</div>
