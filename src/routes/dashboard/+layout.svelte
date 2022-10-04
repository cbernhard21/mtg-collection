<script>
  import '$lib/css/global.css'
  import Header from '$lib/components/Header.svelte';
  import Nav from '$lib/components/Nav.svelte';
  import Aside from '$lib/components/Aside.svelte'
</script>

<div class="page-grid">
  <div class="header">
    <Header />
  </div>
  
  <div class="nav">
    <Nav />
  </div>
  
  <slot></slot>
  
  <div class="aside">
    <Aside />
  </div>
</div>

<style>
  .page-grid {
    display: grid;
    grid-template-columns: min-content 1fr min-content;
    grid-template-rows: min-content 1fr;
    min-height: 100vh;
  }

  .header {
    grid-column: 1/-1;
    align-self: baseline;
    border: 1px solid red;
  }

  .nav {
    border: 1px solid orange;
  }

  .aside {
    border: 1px solid blue;
  }

</style>


