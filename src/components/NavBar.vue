<template>
<!-- TODO: Make the hamburger work -->
<nav class="navbar" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <a class="navbar-item title is-1 has-text-primary" href="#">T/G</a>

    <a role="button" class="navbar-burger burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>

  <div id="navbarBasicExample" class="navbar-menu">
    <div class="navbar-start">
      <a class="navbar-item">Home🏡</a>
      <a class="navbar-item">About Me📚</a>
      <a class="navbar-item">Skills📈</a>
      <a class="navbar-item">Contact👋</a>
    </div>

    <div class="navbar-end">
      <div class="navbar-item">
        <div class="buttons">
          <a class="button is-primary is-medium">
            <span class="icon ">
              <i class="fab fa-github"></i>
            </span>          
          </a>
          <a class="button is-primary is-medium">
            <span class="icon">
              <i class="fab fa-linkedin"></i>
            </span>    
          </a>
        </div>
      </div>
    </div>
  </div>
</nav>
</template>

