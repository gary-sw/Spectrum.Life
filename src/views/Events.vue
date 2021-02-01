<template>
  <div id="home">
    <div class="container-fluid py-5 grey-bg">
      <div class="row d-flex align-items-center wrapper mx-auto">
        <div class="col-md-5 py-5">
          <img src="../assets/logo.png" class="img-fluid" />
        </div>
        <div class="col-md-7">
          <h2 class="purple-text px-5 py-4 text-left">Book an event with us!</h2>
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
            <h1 class="purple-text">Upcoming Events</h1>
          </div>
          <div class="col"><hr class="h-divider" /></div>
        </div>
        <div class="row">
          <div class="col-lg-6 py-3">
            <CardEvent
              title="Virtual Yoga with Gemma Habington"
              date="20"
              month="Jan"
            />
          </div>
          <div class="col-lg-6 py-3">
            <CardEvent title="Event Title to go Here" date="21" month="Jan" />
          </div>
          <div class="col-lg-6 py-3">
            <CardEvent title="Event Title to go Here" date="22" month="Jan" />
          </div>
          <div class="col-lg-6 py-3">
            <CardEvent title="Event Title to go Here" date="22" month="Jan" />
          </div>
          <div class="col-lg-6 py-3">
            <CardEvent title="Event Title to go Here" date="22" month="Jan" />
          </div>
          <div class="col-lg-6 py-3">
            <CardEvent title="Event Title to go Here" date="22" month="Jan" />
          </div>
          <div class="col-lg-6 py-3">
            <CardEvent title="Event Title to go Here" date="22" month="Jan" />
          </div>
          <div class="col-lg-6 py-3">
            <CardEvent title="Event Title to go Here" date="22" month="Jan" />
          </div>
          <div class="col-lg-6 py-3">
            <CardEvent title="Event Title to go Here" date="22" month="Jan" />
          </div>
          <div class="col-lg-6 py-3">
            <CardEvent title="Event Title to go Here" date="22" month="Jan" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>


<script>
import CardEvent from "@/components/CardEvent.vue";

export default {
  name: "Events",
  components: {
    CardEvent,
  },
};
</script>
