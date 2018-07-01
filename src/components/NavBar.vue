<template>
  <!-- NavBar -->
  <nav class="navbar is-fixed-top">

    <!-- Brand / Logo -->
    <div class="navbar-brand">
      <!-- TODO: Add some logo/brand here -->
    </div>

    <!-- Left Side -->
    <div class="navbar-start">
      <div class="navbar-item">
        <router-link to="/">Home</router-link>
      </div>
      <div class="navbar-item">
        <router-link to="/about">About</router-link>
      </div>
      <div class="navbar-item">
        <router-link to="/projects">Projects</router-link>
      </div>
    </div>

    <!--Right Side  -->
    <div class="navbar-end">
      <span class="navbar-item nav-logo">
        <a href="https://github.com/evan-buss" style="font-size: 45px;">
          <i class="fa fa-github"></i>
        </a>
      </span>
    </div>
  </nav>
</template>

<style lang="scss" scoped>
@import "../assets/mystyles";
@import "../../node_modules/bulma/sass/components/navbar";
</style>
