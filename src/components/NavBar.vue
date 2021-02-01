<template>
  <div class="nav-container row">
    <div class="col triangle-div px-0 d-none d-lg-block ">
      <div class="triangle-div-overlap"></div>
    </div>
    <div class="col px-0">
      <b-navbar toggleable="lg" class="purple-bg">
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        <b-collapse id="nav-collapse" is-nav>
          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto">
            <b-nav-item to="">Plans</b-nav-item>
            <b-nav-item to="/events">Events</b-nav-item>
            <b-nav-item to="">EAP</b-nav-item>
            <b-nav-item to="">Wellbeing&nbsp;benefits</b-nav-item>
            <b-nav-item to="">My&nbsp;organisation</b-nav-item>
            <b-nav-item to="">Virtual</b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
  </div>
</template>


<script>
export default {
  name: "NavBar",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.nav-container {
  max-width: 100%;
  margin: 0;
  background-color: #543d6b;
  border-bottom: 8px solid #e4e4e7;
}
.triangle-div {
  width: 0;
  height: 0;
  border-style: solid;
  border-width: 76px 76px 0 0;
  border-color: #e4e4e7 transparent transparent transparent;
}
.triangle-div-overlap {
  position: relative;
  top: -76px;
  left: 0px;
  width: calc(100% + 62px);
  border-style: solid;
  border-width: 76px 76px 0 0;
  border-color: white transparent transparent transparent;
}
ul {
  list-style-type: none;
  margin: 0 20px;
  padding: 0;
}
li {
  display: block;
  padding: 10px 25px;
}
li > a.nav-link {
  white-space: nowrap;
  color: white !important;
}
li > a.nav-link:hover {
  color: whitesmoke !important;
}

</style>
