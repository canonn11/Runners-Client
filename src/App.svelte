
<script>
  import Router from "svelte-spa-router";
  import index from "./index.svelte";
</script>

<main>
  <a href="/" class="text-2xl">홈</a>
  <a href="/#/index">어바웃</a>

  <h1 class="text-3xl font-bold underline">This is Home</h1>

</main>

<Router
  routes={{
    "/index": index,
  }}
/>