<script>
  import HomeLink from "$lib/HomeLink.svelte"

</script>

<HomeLink/>
<nav class="h-16 border-b-4 p-2 border-slate-800">
  <h1 class="text-3xl font-bold text-center mr-5">$Pricing Cards</h1>
</nav>
<!-- Global Container -->
<div class="min-h-screen flex justify-center items-center">
  <!-- Card Container -->
  <div
    class="flex flex-col md:flex-row my-6 space-y-6 md:space-y-0 md:space-x-6 md:my-0">
    <!-- Card 1 -->
    <div
      class="border-8 rounded-2xl flex-grow  flex flex-col text-center p-8 border-slate-600">
      <div class="uppercase">Basic</div>
      <h2 class="text-4xl font-serif font-bold mt-10">100GB</h2>
      <p class="">$1.99/month</p>
      <button
        class=" inline-block border-2 duration-200 border-violet-600 hover:bg-violet-800 hover:border-violet-800 px-10 py-3 my-6 rounded-lg "
        >Purchase</button>
      <ul class="border-t mt-8 border-slate-700 justify-end whitespace-nowrap">
        <li class="mt-8">✓ 100 GB Storage</li>
        <li>✓ Option to add members</li>
        <li>✓ Extra Member Benifits</li>
      </ul>
    </div>

    <!-- Card 2 -->
    <div
      class="border-8 rounded-2xl flex-grow  flex flex-col text-center p-8 border-violet-600">
      <div class="uppercase">Standard</div>
      <h2 class="text-4xl font-serif font-bold mt-10">200GB</h2>
      <p class="">$3.99/month</p>
      <button
        class=" inline-block border-2 duration-200 border-violet-600 bg-violet-600 hover:bg-violet-800 hover:border-violet-800 px-10 py-3 my-6 rounded-lg "
        >Purchase</button>
      <ul
        class="border-t mt-8  border-slate-700 justify-end whitespace-nowrap ">
        <li class="mt-8">✓ 200 GB Storage</li>
        <li>✓ Option to add members</li>
        <li>✓ Extra Member Benifits</li>
      </ul>
    </div>

    <!-- Card 3 -->
    <div
      class="border-8 rounded-2xl flex-grow  flex flex-col text-center p-8 border-slate-600">
      <div class="uppercase">Premium</div>
      <h2 class="text-4xl font-serif font-bold mt-10">2TB</h2>
      <p class="">$8.99/month</p>
      <button
        class=" inline-block border-2 duration-200 border-violet-600 hover:bg-violet-800 hover:border-violet-800 px-10 py-3 my-6 rounded-lg "
        >Purchase</button>
      <ul class="border-t mt-8 border-slate-700 justify-end whitespace-nowrap">
        <li class="mt-8">✓ 2 TB Storage</li>
        <li>✓ Option to add members</li>
        <li>✓ Extra Member Benifits</li>
      </ul>
    </div>
  </div>
</div>
