<template>
  <div class="event-card purple-bg">
    <div class="row align-items-center justify-content-center px-5 py-3">
      <div class="col event-card-title">{{ title }}</div>
      <div class="col-auto text-center">
        <div class="event-card-number">{{ date }}</div>
        <div class="event-card-month">{{ month }}</div>
      </div>
    </div>
    <div class="row mx-0 justify-content-end">
        <a class="pink-bg event-card-link">More information</a>
    </div>
  </div>
</template>

<style>
.event-card {
  color: white;
  border-radius: 10px 10px 0px 10px;
}

.event-card-title {
  font-size: 24px;
  text-align: left;
  overflow: hidden;
  white-space:pre-wrap
}

.event-card-number{
    font-size: 50px;
    line-height: 50px;
}

.event-card-month{
    font-size: 20px;
}


.event-card-link {
    font-weight: bold;
    color: white;
    padding: 10px 20px 10px 30px;
    border-radius: 30px 0px 0px 0px;
    cursor: pointer;
}

.event-card-link:hover {
    color: white;
}
</style>

<script>
export default {
  name: "CardEvent",
  props: {
    date: String,
    month: String,
    title: String,
  },
};
</script>