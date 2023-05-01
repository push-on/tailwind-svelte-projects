<script>
  import emailSub from "$lib/thumbnails/email.webp"
  import imagegallery from "$lib/thumbnails/imagegallary.webp"
  import modal from "$lib/thumbnails/modal.webp"
  import priceCard from "$lib/thumbnails/pricecard.webp"
  import signup from "$lib/thumbnails/signup.webp"
</script>

<div class="flex flex-col space-y-4 border-b-2 border-blue-50/10 pb-2">
  <div class="flex justify-center mt-5">
    <svg
      class="mr-2 text-sky-400"
      xmlns="http://www.w3.org/2000/svg"
      width="3em"
      height="3em"
      viewBox="0 0 24 24"
      ><path
        fill="currentColor"
        d="M12.001 4.8c-3.2 0-5.2 1.6-6 4.8c1.2-1.6 2.6-2.2 4.2-1.8c.913.228 1.565.89 2.288 1.624C13.666 10.618 15.027 12 18.001 12c3.2 0 5.2-1.6 6-4.8c-1.2 1.6-2.6 2.2-4.2 1.8c-.913-.228-1.565-.89-2.288-1.624C16.337 6.182 14.976 4.8 12.001 4.8zm-6 7.2c-3.2 0-5.2 1.6-6 4.8c1.2-1.6 2.6-2.2 4.2-1.8c.913.228 1.565.89 2.288 1.624c1.177 1.194 2.538 2.576 5.512 2.576c3.2 0 5.2-1.6 6-4.8c-1.2 1.6-2.6 2.2-4.2 1.8c-.913-.228-1.565-.89-2.288-1.624C10.337 13.382 8.976 12 6.001 12z" /></svg>
    <h1 class="text-5xl font-bold">Tailwind Projects</h1>
  </div>
  <p class="text-center">
    All sites are
    <strong class="text-cyan-300 underline underline-offset-4"> mobile </strong> &
    <strong class="text-cyan-300 underline underline-offset-4"> desktop </strong>
    friendly.
  </p>
</div>

<div class="flex justify-center decoration-4">
  <!-- list of pages in tailwind css grid -->
  <div
    class="font-bold container grid sm:grid-cols-2 lg:grid-cols-3 p-5 m-5 gap-4 text-xl whitespace-nowrap">
    <a
      class=" p-5 hover:underline underline-offset-8 capitalize text-center bg-slate-700/10 backdrop-blur border-slate-700 border hover:bg-slate-100/10 hover:shadow-2xl hover:shadow-black rounded-xl min-w-fit decoration-sky-400 space-"
      href="./emailsub/">
      <img class="mb-4 rounded-3xl" src={emailSub} alt="" />
      Email Sub
    </a>
    <a
      class=" p-5 hover:underline underline-offset-8 capitalize text-center bg-slate-700/10 backdrop-blur border-slate-700 border hover:bg-slate-100/10 hover:shadow-2xl hover:shadow-black rounded-xl min-w-fit decoration-sky-400"
      href="./imagegallery/">
      <img class="mb-4 rounded-3xl" src={imagegallery} alt="" />
      Image Gallery</a>
    <a
      class=" p-5 hover:underline underline-offset-8 capitalize text-center bg-slate-700/10 backdrop-blur border-slate-700 border hover:bg-slate-100/10 hover:shadow-2xl hover:shadow-black rounded-xl min-w-fit decoration-sky-400"
      href="./loginmodal/">
      <img class="mb-4 rounded-3xl" src={signup} alt="" />

      Login Modal</a>
    <a
      class=" p-5 hover:underline underline-offset-8 capitalize text-center bg-slate-700/10 backdrop-blur border-slate-700 border hover:bg-slate-100/10 hover:shadow-2xl hover:shadow-black rounded-xl min-w-fit decoration-sky-400"
      href="./pricingcard/">
      <img class="mb-4 rounded-3xl" src={priceCard} alt="" />
      Pricing Card</a>
    <a
      class=" p-5 hover:underline underline-offset-8 capitalize text-center bg-slate-700/10 backdrop-blur border-slate-700 border hover:bg-slate-100/10 hover:shadow-2xl hover:shadow-black rounded-xl min-w-fit decoration-sky-400"
      href="./productModal/">
      <img class="mb-4 rounded-3xl" src={modal} alt="" />
      Product modal</a>
  </div>
</div>
