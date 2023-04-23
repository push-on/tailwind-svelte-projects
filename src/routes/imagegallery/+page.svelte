<script>
  import HomeLink from "$lib/HomeLink.svelte"
  import img1 from "$lib/assets/imgs/1.jpg"
  import img2 from "$lib/assets/imgs/2.jpg"
  import img3 from "$lib/assets/imgs/3.jpg"
  import img4 from "$lib/assets/imgs/4.jpg"
  import img5 from "$lib/assets/imgs/5.jpg"
  import img6 from "$lib/assets/imgs/6.jpg"


  let list = [img1, img2, img3, img4, img5, img6]
</script>

<HomeLink />
<div class="flex justify-center items-center min-h-screen">
  <div class="p-4 grid gap-4 sm:grid-cols-2 xl:grid-cols-3">
    {#each list as img}
      <img src={img} alt="" class="rounded-lg" />
      
    {/each}
  </div>
</div>
