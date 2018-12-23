<template>
  <div id="app">
   

<nav class="navbar is-transparent has-background-grey-dark">
  <div class="navbar-brand">
    
    <div class="navbar-burger burger" data-target="navbarExampleTransparentExample">
      <span></span>
      <span></span>
      <span></span>
    </div>
  </div>

  <div id="navbarExampleTransparentExample" class="navbar-menu">
  <span class="icon">
  <i class="fas fa-home"></i>
</span>
    <div class="navbar-start">
      <a class="navbar-item is-active has-text-grey-light" href="https://bulma.io/">
        Home
      </a>
      <div class="navbar-item has-dropdown is-hoverable ">
        <a class="navbar-link has-text-grey-light is-hoverable" href="https://bulma.io/documentation/overview/start/">
          About us
        </a>
        <div class="navbar-dropdown is-boxed">
          <a class="navbar-item" href="https://bulma.io/documentation/overview/start/">
            Contact
          </a>
          
          <hr class="navbar-divider">
          <a class="navbar-item" href="https://bulma.io/documentation/elements/box/">
            Report an issue
          </a>
          <a class="navbar-item is-active" href="https://bulma.io/documentation/components/breadcrumb/">
            
          </a>
        </div>
      </div>
    </div>

    <div class="navbar-end">
      <div class="navbar-item">
        <div class="field is-grouped">
          <p class="control">
            <a class="bd-tw-button button has-background-light" data-social-network="Twitter" data-social-action="tweet" data-social-target="http://localhost:4000" target="_blank" href="https://twitter.com/intent/tweet?text=Bulma: a modern CSS framework based on Flexbox&amp;hashtags=bulmaio&amp;url=http://localhost:4000&amp;via=jgthms">
              <span class="icon">
                <i class="fab fa-twitter"></i>
              </span>
              <span>
                Log In
              </span>
            </a>
          </p>
          <p class="control">
            <a class="button is-warning" href="https://github.com/jgthms/bulma/releases/download/0.7.2/bulma-0.7.2.zip">
              <span class="icon">
                <i class="fas fa-download"></i>
              </span>
              <span>Sign Up</span>
            </a>
          </p>
        </div>
      </div>
    </div>
  </div>
</nav>
   <hr>
   <!-- BODY-->


   <div class="columns is-mobile is-centered">
  <div class="column is-half">
    <p class="bd-notification is-primary">
      <button class="button is-large is-dark"> Post it already!  :) </button>
    </p>
  </div>
</div>
     
<!-- TAGS-->
 <section class="section">
    <div class="container is-light-gray is-centered">
      
      <h2 class="subtitle">
        Tags
      </h2>
      <span class="tag is-black">PHP </span>
<span class="tag is-dark is-medium">Laravel</span>
<span class="tag is-light">Vue</span>
<span class="tag is-white is-medium">React</span>
<span class="tag is-primary">Javascript</span>
<span class="tag is-link is-medium">Git</span>
<span class="tag is-info">Python</span>
<span class="tag is-success">Css</span>
<span class="tag is-warning">HTML</span>
<span class="tag is-danger">Danger</span>
    </div>
  </section>
  <hr>

    <!--footer-->

    <footer class="footer">
  <div class="content has-text-centered">
    <p>
      <strong>Made at Adeva First Female Bootcamp</strong> 
      <a href="https://femalebootcamp.adevait.com/">'18</a>
    </p>
  </div>
</footer>
   
  </div>
</template>

<script>


export default {
  name: 'app',
  
  
}
</script>

<style lang="scss">
@import "~bulma/css/bulma.css";
</style>
