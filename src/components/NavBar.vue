<template>
  <div class="">
    <b-navbar toggleable="lg" type="dark" class="purple-bg">
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav>
        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-item to="/plans">Plans</b-nav-item>
          <b-nav-item to="">Events</b-nav-item>
          <b-nav-item to="">EAP</b-nav-item>
          <b-nav-item to="">Wellbeing benefits</b-nav-item>
          <b-nav-item to="">My organisation</b-nav-item>
          <b-nav-item to="">Virtual</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>


<script>
export default {
  name: "NavBar",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
nav{
  border-bottom: 8px solid #e4e4e7;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 5px 20px;
}
</style>
