<script>
  export let title;
  export let description;
</script>

<h1>{title}</h1>
<slot />

<svelte:head>
  <title>{title} | Bonfire</title>
  <meta name="description" content={description} />
</svelte:head>
