<template>
  <div>
    <b-navbar toggleable="lg" type="dark" class="px-4 fixed-top shadow nav-color" shadow>
      <b-navbar-toggle target="nav-collapse" class="ms-auto"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav class="justify-content-center">
        <b-navbar-nav>
          <b-nav-item href="#home">Home</b-nav-item>
          <b-nav-item href="#aboutus">About Us</b-nav-item>
          <b-nav-item href="#service">Service</b-nav-item>
          <b-nav-item href="#contactus">Contanct Us</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: 'NavBar',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .nav-color{
    background-color: #1A4D8C;
    color: white;
  }
</style>
