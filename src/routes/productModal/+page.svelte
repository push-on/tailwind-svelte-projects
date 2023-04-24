<script>
  import HomeLink from "$lib/HomeLink.svelte"
  import headphone from "$lib/assets/headphones.webp"
</script>

<HomeLink />
<nav class="h-16 border-b-4 p-2 border-slate-800">
  <h1 class="text-3xl font-bold text-center mr-5">📦Product Modal</h1>
</nav>
<!-- Global Container -->
<div class="flex items-center justify-center min-h-screen">
  <!-- Card Container -->
  <div
    class="flex flex-col p-6 m-3 space-y-10 bg-slate-800 rounded-2xl shadow-2xl shadow-black md:flex-row md:space-y-0 md:space-x-10 md:m-0 md:p-16">
    <!-- Image Div -->
    <div>
      <img
        src={headphone}
        alt="headphones"
        class="mx-auto duration-200 w-60 hover:scale-105" />
    </div>

    <!-- Content -->
    <div class="flex flex-col space-y-6">
      <!-- Label & Title Container -->
      <div class="flex flex-col mb-4 space-y-3 text-center md:text-left">
        <div>
          <div
            class="inline-block px-3 py-1 text-sm text-white bg-black rounded-full">
            Free Shipping
          </div>
        </div>

        <!-- Title -->
        <div class="max-w-sm text-2xl font-medium">
          Razer Kraken Kitty Edt Gaming Headset Quartz
        </div>
        <!-- Price Container -->
        <div class="flex flex-col mb-4 space-y-3 text-center md:text-left">
          <p class="line-through">$799</p>
          <p class="text-5xl font-bold">$599</p>
          <p class="text-sm font-light text-gray-400">
            This offer is valid until April 3rd or as long as stock lasts!
          </p>
        </div>

        <!-- Button Group -->
        <div class="group">
          <button
            class="w-full transition-all duration-150 bg-blue-700 text-white border-b-8 border-b-blue-700 rounded-lg group-hover:border-t-8 group-hover:border-b-0 group-hover:bg-blue-700 group-hover:border-t-blue-700 group-hover:shadow-lg">
            <div
              class="px-8 py-4 duration-150 bg-blue-500 rounded-lg group-hover:bg-blue-700">
              Add to cart
            </div>
          </button>
        </div>

        <!-- Stock -->
        <div class="flex items-center space-x-3 group">
          <div
            class="w-3 h-3 bg-green-400 rounded-full group-hover:animate-ping" />
          <div class="text-sm">50+ pcs. in stock</div>
        </div>

        <!-- Bottom Buttons Container -->
        <div
          class="flex flex-col space-y-4 md:space-y-0 md:space-x-4 md:flex-row">
          <button
            class="flex items-center justify-center py-3 px-5 space-x-3 border-2 border-gray-300 rounded-lg shadow-sm hover:bg-opacity-30 hover:shadow-lg hover:-translate-y-0.5 transition-all duration-150">
            <svg
              width="25"
              fill="none"
              stroke="currentColor"
              stroke-width="1.5"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
              aria-hidden="true">
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M2.25 3h1.386c.51 0 .955.343 1.087.835l.383 1.437M7.5 14.25a3 3 0 00-3 3h15.75m-12.75-3h11.218c1.121-2.3 2.1-4.684 2.924-7.138a60.114 60.114 0 00-16.536-1.84M7.5 14.25L5.106 5.272M6 20.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm12.75 0a.75.75 0 11-1.5 0 .75.75 0 011.5 0z" />
            </svg>
            <span>Add to cart</span>
          </button>

          <button
            class="flex items-center justify-center py-3 px-5 space-x-3 border-2 border-gray250 rounded-lg shadow-sm hover:bg-opacity25 hover:shadow-lg hover:-translate-y-0.5 transition-all duration-150">
            <svg
              width="25"
              fill="none"
              stroke="currentColor"
              stroke-width="1.5"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
              aria-hidden="true">
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M21 8.25c0-2.485-2.099-4.5-4.688-4.5-1.935 0-3.597 1.126-4.312 2.733-.715-1.607-2.377-2.733-4.313-2.733C5.1 3.75 3 5.765 3 8.25c0 7.22 9 12 9 12s9-4.78 9-12z" />
            </svg>
            <span>Add to wishlist</span>
          </button>
        </div>
      </div>
    </div>
  </div>
</div>
