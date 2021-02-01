<template>
  <div id="home">
    <div class="container-fluid py-5 grey-bg">
      <div class="row d-flex align-items-center wrapper mx-auto">
        <div class="col-md-5 py-5">
          <img src="../assets/logo.png" class="img-fluid" />
        </div>
        <div class="col-md-7">
          <h2 class="purple-text px-5 py-4 text-left">Series A Title</h2>
          <p class="px-5 pb-3 text-left">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam, quis nostrud exercitation ullamco
          </p>
          <a class="mr-5 float-md-right floating-link">See next series</a>
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
          <strong class="grey-text"
            >Upcoming virtual events you can take part in</strong
          >
        </p>
        <div class="row">
          <div class="col-lg-4 py-3">
            <CardEvent
              title="Virtual Yoga with Gemma Habington"
              date="20"
              month="Jan"
            />
          </div>
          <div class="col-lg-4 py-3">
            <CardEvent title="Event Title to go Here" date="21" month="Jan" />
          </div>
          <div class="col-lg-4 py-3">
            <CardEvent title="Event Title to go Here" date="22" month="Jan" />
          </div>
        </div>
      </div>
    </div>
    <div class="container-fluid py-5 grey-bg">
      <div class="row d-flex align-items-center wrapper mx-auto">
        <div class="col-md-7 text-left">
          <h1 class="purple-text px-5 pb-4">Learning</h1>
          <div class="d-md-none">
            <img src="../assets/pillow.png" class="img-fluid" />
          </div>
          <h2 class="purple-text px-5 py-4">Wellbeing Course Title</h2>
          <p class="px-5 pb-5 mr-5">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam, quis nostrud exercitation ullamco
          </p>
          <div class="mx-md-5 text-center text-lg-left  ">
            <a class="mx-md-auto  floating-link">See next series</a>
          </div>
        </div>
        <div class="col-md-5 py-5 d-none d-md-block">
          <img src="../assets/pillow.png" class="img-fluid" />
        </div>
      </div>
    </div>
    <div class="container-fluid py-5">
      <div class="wrapper mx-auto">
        <div class="row py-5">
          <div class="col-md-auto">
            <h1 class="purple-text break-word">Downloadable Guides</h1>
          </div>
          <div class="col"><hr class="h-divider" /></div>
        </div>
        <div class="row px-3">
          <div class="col-lg-3 col-md-6"><CardGuide /></div>
          <div class="col-lg-3 col-md-6"><CardGuide /></div>
          <div class="col-lg-3 col-md-6"><CardGuide /></div>
          <div class="col-lg-3 col-md-6"><CardGuide /></div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.break-word {
  word-break: break-all;
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
