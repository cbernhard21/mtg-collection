<div class="nav-container">
  <figure>
    <img src="images/logos/mtg-logo.png" alt="Green Logo">
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
    padding: 2rem 1rem 0 2rem;
    text-align: right;
  }
  
  a:link,
  a:visited {
    text-decoration: none;
    display: inline-block;
    font-size: 1.6rem;
    color: var(--white);
    transition: all .2s ease-in-out;
  }

  ul {
    display: flex;
    flex-direction: column;
    gap: 3rem;
  }

  li {
    border-bottom: 2px solid transparent;
    transition: all .2s ease-in-out;
    padding-left: 1rem;
    width: 100%;
  }

  li:hover {
    border-bottom: 2px solid black;
  }

</style>