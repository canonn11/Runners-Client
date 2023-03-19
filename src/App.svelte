
<script>
  import Router from "svelte-spa-router";
  import index from "./index.svelte";
</script>

<main>
  <a href="/">홈</a>
  <a href="/#/index">어바웃</a>
</main>

<Router
  routes={{
    "/index": index,
  }}
/>