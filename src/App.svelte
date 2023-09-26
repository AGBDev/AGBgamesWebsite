<script lang="ts">
  import WebsiteTitle from "./lib/WebsiteTitle.svelte";
  import Blog from "./lib/blog/Blog.svelte";
  import ButtonBar from "./lib/buttonbar/ButtonBar.svelte";
</script>

<main>
  <ButtonBar />
  <br />
  <br />
  <WebsiteTitle title="News, Auftritte und Blog" visible={true} size={1} />

  <Blog />
</main>

<style>
  .gfg {
    margin: 1%;
    position: relative;
  }

  /*This CSS code is defining the styles for a container that holds text*/
  .text-container {
    position: absolute;
    color: rgb(255, 255, 255);
    left: 43rem;
    top: 33rem;
    /* background-color: rgb(41, 41, 41, 0.8); */
    padding: 1 1rem;
  }
</style>
