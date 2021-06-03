<template>
  <div id="wrapper">
    <nav class="navbar is-dark">
      <div class="navbar-brand">
        <NuxtLink to="/" class="navbar-item"><strong>Djackets</strong></NuxtLink>
        <a class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbar-menu">
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>
      </div>
      <div class="navbar-menu" id="navbar-menu">
        <div class="navbar-end">
          <NuxtLink to="/summer" class="navbar-item">Summer</NuxtLink>
          <NuxtLink to="/winter" class="navbar-item">Winter</NuxtLink>

          <div class="navbar-item">
            <div class="buttons">
              <NuxtLink to="/log-in" class="button is-light">Log in</NuxtLink>
              <NuxtLink to="/cart" class="button is-success">
                <span class="icon"><i class="fas fa-shopping-cart"></i></span>
              </NuxtLink>
            </div>
          </div>
        </div>
      </div>
    </nav>
    <Nuxt />
  </div>
</template>
