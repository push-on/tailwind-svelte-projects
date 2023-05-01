<script lang="ts">
  import HomeLink from "$lib/HomeLink.svelte"
  import { onMount } from "svelte"

  let images: string[] = []

  onMount(async () => {
    const imageFiles = import.meta.glob("../../imgs/*.{webp}")
    for (const path in imageFiles) {
      const image: any = await imageFiles[path]()
      images = [...images, image.default]
    }
  })
</script>


<HomeLink />
<nav class="h-16 border-b-4 p-2 border-slate-800">
  <h1 class="text-3xl font-bold text-center mr-5">Image Gallery</h1>
</nav>
<div class="flex justify-center items-center min-h-screen">
  <div class="p-4 grid gap-4 sm:grid-cols-2 xl:grid-cols-3">
    {#each images as img}
      <img src={img} alt="" class="rounded-lg" />
    {/each}
  </div>
</div>

<div>

</div>