<template>
  <b-navbar
  toggleable="md"
  type="dark"
  variant="info">
  <b-navbar-brand :to="{ name: 'Home' }">AvaAccounting Home</b-navbar-brand>
  <b-navbar-nav>
    <b-nav-item href="#">User actions</b-nav-item>
    <b-nav-item href="#">User actions</b-nav-item>
  </b-navbar-nav>
  </b-navbar>
</template>
<script>
export default {
  name: 'Navbar',
};
</script>
