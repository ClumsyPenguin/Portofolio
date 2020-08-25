<template>
  <div>
    <b-button class="hamburger-button" v-b-toggle.sidebar-1>
      <font-awesome-icon icon="bars"/>
    </b-button>
    <b-sidebar id="sidebar-1" bg-variant="dark" text-variant="light" backdrop shadow>
      <b-navbar-nav>
          <b-nav-item class="nav-link" href="/">Home</b-nav-item>
          <b-nav-item class="nav-link" href="/projects">Projects</b-nav-item>
          <b-nav-item class="nav-link" href="/about">About</b-nav-item>
          <b-nav-item class="nav-link" href="/contact">Contact</b-nav-item>
        </b-navbar-nav>
    </b-sidebar>
  </div>
</template>

<style>
.nav-link{
  text-align: center;
  color:white !important;
  text-decoration: none;
  margin: 10px;
}
.hamburger-button{
  font-size: 50px !important; 
  background-color: transparent !important;
  border-color: transparent !important;
  border: none !important;
}
</style>

<script>

</script>