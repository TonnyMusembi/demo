<template>
<nav>
  <nav class="navbar navbar-inverse">
    <ul class="nav menu">
      <li>
        <router-link to="/about" @click.native="closeNavBarFromChild">About</router-link>
      </li>
      <li class="hidden-lg hidden-md">
        <router-link to="/product" @click.native="closeNavBarFromChild">Product</router-link>
      </li>
    </ul>
  </nav>
</nav>
  <button>
  </button>
</template>

<script>
import from "@/components/HelloWorld";"./@components/Helloworl.vue "
export default {
  name: "Navbar",





}
</script>

<style scoped>

</style>