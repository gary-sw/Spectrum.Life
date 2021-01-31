<template>
  <footer class="container-fluid py-5 grey-bg ">
      <div class="d-flex align-items-center justify-content-end py-5 wrapper mx-auto">
          <a href="#">Privacy Policy</a>
          <div class="v-divider"></div>
          <a href="#"> Terms &amp; Conditions</a>
      </div>
  </footer>
</template>


<script>
export default {
  name: "Footer",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
a{
  color: darkgrey;
  font-weight: bold;
}

a:hover{
  color: #543d6b;
}

.v-divider{
  border-left: 2px darkgrey solid;
  height: 20px;
  margin-left: 10px;
  margin-right: 10px;
}
</style>
