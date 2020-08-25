<template>
  <div>
    <b-button v-b-toggle.sidebar-1>☰</b-button>
    <b-sidebar id="sidebar-1" bg-variant="dark" text-variant="light" backdrop shadow>
      <b-navbar-nav>
          <b-nav-item href="/">Home</b-nav-item>
          <b-nav-item href="/projects">Projects</b-nav-item>
          <b-nav-item href="/about">About</b-nav-item>
          <b-nav-item href="/contact">Contact</b-nav-item>
        </b-navbar-nav>
    </b-sidebar>
  </div>
</template>

<style>
a{
  display: flex;
  text-align: center;
  color:white !important;
  text-decoration: none;
  margin: 10px;
}
button{
  font-size: 50px !important; 
  background-color: transparent !important;
  border-color: transparent !important;
  border: none !important;
}
</style>