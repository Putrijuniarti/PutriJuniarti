<template>
  <nav class="navbar navbar-expand-lg bg-body-tertiary" style="font-family: Avenir, Helvetica, Arial, sans-serif">
    <div class="container-fluid">
      <a class="navbar-brand" href="/">Putri Juniarti</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">

          <li class="nav-item">
            <a class="nav-link" href="/profile">Profile</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/about">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <router-view></router-view>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

nav a{
  font-size:15pt;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  font-weight: bold;
}

</style>
