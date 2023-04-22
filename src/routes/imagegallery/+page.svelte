<script>
  import HomeLink from "$lib/HomeLink.svelte"
  const files = import.meta.glob("$lib/imgs/*.*")

  // Get the list of file paths
  const list = Object.keys(files).map((path) => {
    return {
      path: path,
      name: path.split("/").pop(), // Get the file name from the path
    }
  })
</script>

<HomeLink />
<div class="flex justify-center items-center min-h-screen">
  <div class="p-4 grid gap-4 sm:grid-cols-2 xl:grid-cols-3">
    {#each list as img}
      <!-- Image -->
      <img src={img.path} alt={img.name} class="rounded-lg" />
    {/each}
  </div>
</div>
