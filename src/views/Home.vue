<template>
  <div id="home">
    <div class="container-fluid py-5 grey-bg">
      <div class="row d-flex align-items-center wrapper mx-auto">
        <div class="col py-5">
          <img src="../assets/logo.png" class="img-fluid" />
        </div>
        <div class="col-7">
          <h2 class="purple-text px-5 py-4 text-left">Series A Title</h2>
          <p class="px-5 pb-3 text-left">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam, quis nostrud exercitation ullamco
          </p>
          <a class="mr-5 float-right floating-link">See next series</a>
        </div>
      </div>
    </div>
    <div class="container-fluid py-5 px-5">
      <div class="wrapper mx-auto">
        <div class="row py-4">
          <div class="col-md-auto">
            <h1 class="purple-text">Virtual Events</h1>
          </div>
          <div class="col"><hr class="h-divider" /></div>
        </div>
        <p class="text-left pt-2 pb-5">
          <strong class="grey-text">Upcoming virtual events you can take part in</strong>
        </p>
        <div class="row">
          <div class="col">
            <CardEvent title="Virtual Yoga with Gemma Habington" date="20" month="Jan" />
          </div>
          <div class="col">
            <CardEvent title="Event Title to go Here" date="21" month="Jan" />
          </div>
          <div class="col">
            <CardEvent title="Event Title to go Here" date="22" month="Jan" />
          </div>
        </div>
      </div>
    </div>
    <div class="container-fluid py-5 grey-bg">
      <div class="row d-flex align-items-center wrapper mx-auto">
        <div class="col-7 text-left">
          <h1 class="purple-text px-4 pb-4 ">Learning</h1>
          <h2 class="purple-text px-5 py-4 ">Wellbeing Course Title</h2>
          <p class="px-5 pb-5 mr-5">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam, quis nostrud exercitation ullamco
          </p>
          <a class="mx-4 float-left floating-link">See next series</a>
        </div>
        <div class="col py-5">
          <img src="../assets/pillow.png" class="img-fluid" />
        </div>
      </div>
    </div>
    <div class="container-fluid py-5">
      <div class="wrapper mx-auto">
        <div class="row py-5">
          <div class="col-md-auto">
            <h1 class="purple-text">Downloadable Guides</h1>
          </div>
          <div class="col"><hr class="h-divider" /></div>
        </div>
        <div class="row">
          <div class="col"><CardGuide /></div>
          <div class="col"><CardGuide /></div>
          <div class="col"><CardGuide /></div>
          <div class="col"><CardGuide /></div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
h1 {
  letter-spacing: 15px;
  text-transform: uppercase;
  font-weight: bold;
  font-family: Impact, Haettenschweiler, "Arial Narrow Bold", sans-serif;
}

h2 {
  font-weight: 900;
  font-family: Arial, Helvetica, sans-serif;
}

p {
  font-size: 20px;
  color: #111;
}

.h-divider {
  min-width: 100%;
  border-top: 3px solid #f4f4f4;
  margin-top: 24px;
}

.floating-link {
  font-size: 1.5rem;
  letter-spacing: 0.6px;
  color: #d72d87;
  border-bottom: 3px solid #d72d87;
  font-weight: bold;
  cursor: pointer;
}

.floating-link:hover {
  color: #d72d87;
  text-decoration: none;
}
</style>

<script>
import CardGuide from "@/components/CardGuide.vue";
import CardEvent from "@/components/CardEvent.vue";

export default {
  name: "Home",
  components: {
    CardGuide,
    CardEvent,
  },
};
</script>
