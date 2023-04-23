<script>
  import HomeLink from "$lib/HomeLink.svelte"
  import image1 from "$lib/assets/imgs/1.jpg"
  import image2 from "$lib/assets/imgs/2.jpg"
  import image3 from "$lib/assets/imgs/3.jpg"
  import image4 from "$lib/assets/imgs/4.jpg"
  import image5 from "$lib/assets/imgs/5.jpg"
  import image6 from "$lib/assets/imgs/6.jpg"


  let list = [image1, image2, image3, image4, image5, image6]
</script>

<HomeLink />
<div class="flex justify-center items-center min-h-screen">
  <div class="p-4 grid gap-4 sm:grid-cols-2 xl:grid-cols-3">
    {#each list as img}
      <img src={img} alt="" class="rounded-lg" />
      
    {/each}
  </div>
</div>
