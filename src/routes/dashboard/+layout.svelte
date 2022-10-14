<script>
  import '$lib/css/global.css'
  import Header from '$lib/components/Header.svelte';
  import Nav from '$lib/components/Nav.svelte';
  import Aside from '$lib/components/Aside.svelte'
</script>

<svelte:head>
  <title>MTG Collection</title>
</svelte:head>

<div class="page-grid">
  <div class="header">
    <Header />
  </div>
  
  <div class="nav">
    <Nav />
  </div>
  
  <div class="main-container">
    <slot></slot>
  </div>
  
  
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
    grid-column: 2/-1;
    align-self: baseline;
    border: 1px solid red;
  }

  .nav {
    grid-row: 1/3;
  }

  .main-container {
    grid-row: 2/-1;
    grid-column: 2/3;
    border: 1px solid tomato;
  }

  .aside {
    border: 1px solid blue;
    grid-row: 2/3;
    grid-column: 3/4;
  }

</style>


