<script setup lang="ts">
import "bootstrap/dist/css/bootstrap.min.css";
import "bootstrap/dist/js/bootstrap.min.js";
</script>
<template>
  <nav class="navbar navbar-expand-lg navbar-light">
  <div class="container">
    <router-link to="/"  class="navbar-brand">
      <img src="/assets/CBR-samen-vooruit.png" class="logo img-fluid">
    </router-link>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <router-link to="/" class="nav-link">Home</router-link>
        </li>
        <li class="nav-item">
          <router-link to="/alternatives" class="nav-link">Vervoers alternatieven</router-link>
        </li>
        <li class="nav-item">
          <router-link to="/enquete" class="nav-link">Enquete invullen</router-link>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>
<style>
.navbar.navbar-expand-lg{
  height: 95px;
  background-color: #ffffff;
}
.logo.img-fluid{
  width: 170px;
}
.nav-item .nav-link{
  color: #003DA5;
  font-weight: bolder;
}
.nav-item .nav-link:hover{
  color: #FF8200;
}
.navbar-nav > li{
  margin-left:30px;
  margin-right:30px;
}
@media only screen and (max-width: 768px) {
  .navbar.navbar-expand-lg .container{
    background-color: #ffffff;
  }
}
</style>