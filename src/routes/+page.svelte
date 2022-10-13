<script>
  import '$lib/css/global.css';

  function handleLogin() {
    console.log('you are logged in!!!')
  }

</script>

<main>

  <form class="login-form">
    <h1>Please Log In</h1>
    <div class="form-group">
      <label for="username">Username</label>
      <input type="text" name="username" id="password" placeholder="Username">
    </div>
    <div class="form-group">
      <label for="password">Password</label>
      <input type="text" name="password" id="password" placeholder="Password">
    </div>
    <a href="/dashboard" on:click={handleLogin} class="btn login">Login</a>    
  </form>

</main>

<style>
  main {
    width: 100%;
    min-height: 100vh;
    background-image: url(images/bg-login-1.jpg);
    /* background-image: url(images/bg-login-2.jpg); */
    /* background-image: url(images/bg-login-3.jpg); */
    /* background-image: url(images/bg-login-4.png); */
    /* background-image: url(images/bg-login-5.jpg); */
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  h1 {
    font-size: 3.6rem;
  }

  .login-form {
    backdrop-filter: blur(20px);
    padding: 4rem;
    border-radius: 10px;
    display: flex;
    flex-direction: column;
    gap: 2rem;
    width: 500px;
  }

  .form-group {
    display: flex;
    flex-direction: column;
  }

  label {
    font-size: 1.8rem;
    color: var(--white);
    font-weight: 300;
  }

  input {
    padding: .5rem .25rem;
    font-size: 1.6rem;;
  }

  .btn.login {
    text-align: center;
    font-size: 1.6rem;
    transition: all .2s ease-in-out;
  }

  .login:hover {
    background-color: #000000;
  }

</style>

