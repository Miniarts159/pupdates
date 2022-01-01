<script>
  import SayHeckin from "$lib/components/SayHeckin.svelte";
</script>

{#each [1, 2, 3, 4, 5].map((y) => y + "") as x}
  <SayHeckin name={x} />
{/each}

<SayHeckin />
