<script lang="ts">
  import HomeLink from "$lib/HomeLink.svelte"
  import { onMount } from "svelte"

  let images: string[] = []

  onMount(async () => {
    const imageFiles = import.meta.glob("../../imgs/*.{jpg,png,gif}")
    for (const path in imageFiles) {
      const image: any = await imageFiles[path]()
      images = [...images, image.default]
    }
  })
</script>

<HomeLink />
<div class="flex justify-center items-center min-h-screen">
  <div class="p-4 grid gap-4 sm:grid-cols-2 xl:grid-cols-3">
    {#each images as img}
      <img src={img} alt="" class="rounded-lg" />
    {/each}
  </div>
</div>
