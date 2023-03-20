
<script>
  import Router from "svelte-spa-router";
  import index from "./routes/index.svelte";
  import test from "./routes/test.svelte";
  import Marathon from "./routes/Marathon.svelte";
</script>



<Router
  routes={{
    "/": index,
    "/test":test,
    "/marathon":Marathon
  }}
/>