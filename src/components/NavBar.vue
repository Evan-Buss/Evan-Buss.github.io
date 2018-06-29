<template>
  <!-- NavBar -->
  <nav class="navbar is-fixed-top is-dark">

    <!-- Brand / Logo -->
    <div class="navbar-brand">
      <a class="navbar-item" href="https://bulma.io">
        <img src="https://bulma.io/images/bulma-logo.png" alt="Bulma" width="112" height="28">
      </a>
    </div>

    <!-- Left Side -->
    <div class="navbar-start">
      <div class="navbar-item">
        <router-link to="/">Home</router-link>
      </div>
      <div class="navbar-item">
        <router-link to="/about/Evan">About</router-link>
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
nav {
  overflow: hidden;
  width: 100%;
  height: 50px;

  a {
    float: left;
    display: block;
    color: #f2f2f2;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    font-size: 18px;

    &:hover {
      background: #ddd;
      color: black;
    }
  }
}
</style>
