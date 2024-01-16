<script setup>
import { ref, defineProps } from "vue";

const navItems = [
  { id: 1, nav: "Home" },
  { id: 2, nav: "About" },
  { id: 3, nav: "Services" },
  { id: 4, nav: "Team" },
  { id: 5, nav: "Portfolio" },
  { id: 6, nav: "Contact" },
  { id: 7, nav: "Blog" },
  { id: 8, nav: "Single" },
];
</script>

<template>
  <nav class="nav fixed-top">
    <div class="container-fluid nav-background">
      <div class="container d-flex justify-conten-between gap-5 px-5 py-4">
        <a class="navbar-brand flex-grow-1"><img class=" pb-0 mb-0" src="/images/logo.png" alt=""></a>
        <div class="d-flex justify-content-between gap-5">
            <div class="navbar-nav d-flex justify-content-center" v-for="navItem in navItems">
              <a :href="navItem.id" :key="navItem.id" id="navItem.id" class="a_link">{{
                navItem.nav
              }}</a>
            </div>
        </div>
      </div>
    </div>
  </nav>
</template>

<style scoped>

.nav a{
  padding-bottom: 5px ;
}
/* .nav a:hover {
  border-bottom: 2px solid white;
  } */
</style>