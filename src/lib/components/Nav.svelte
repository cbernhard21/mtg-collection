<div class="nav-container">
  <figure>
    <img src="images/logos/black-logo.png" alt="Green Logo">
  </figure>
  <nav class="main-nav">
    <ul class="nav-list">
      <li class="nav-item"><a href="/dashboard">Dashboard</a></li>
      <li class="nav-item"><a href="/dashboard/search">Search</a></li>
      <li class="nav-item"><a href="/dashboard/collection">Collection</a></li>
      <li class="nav-item"><a href="/dashboard">Profile</a></li>
      <li class="nav-item"><a href="/">Log Out</a></li>
    </ul>
  </nav>
</div>





<style>

  .nav-container {
    padding: 1rem;
    background-color: var(--bg-nav);
    height: 100%;
  }

  figure {
    margin-bottom: 3rem;
  }

  nav {
    height: 100%;
    padding: 2rem 1rem 0 2rem;
    text-align: right;
  }
  
  a:link,
  a:visited {
    text-decoration: none;
    display: inline-block;
    font-size: 1.6rem;
    color: blue;
  }

  ul {
    display: flex;
    flex-direction: column;
    gap: 3rem;
  }

  li {
    border-bottom: 1px solid black;
  }

</style>