<script>
  import Nav from '../components/Nav.svelte'

  export let segment
</script>

<style>
  main {
    position: relative;
    background-color: white;
    min-height: 80vh;
    box-sizing: border-box;
  }
</style>

<Nav {segment} />

<main>
  <slot />
</main>
