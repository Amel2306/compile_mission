<template>
  <div id="app">
    <div id="introduction" class="relative">
      <img
        id="group-points"
        src="@/assets/images/group_points.png"
        class="hidden md:block left-16 top-20 md:top-[640px] absolute"
      />
      <HeaderComponent />   
      <HomeIntroduction />
    </div>
    <FeaturesComponent />
  </div>
</template>

<script>
import HeaderComponent from "./components/HeaderComponent.vue";
import FeaturesComponent from "./components/FeaturesComponent.vue";
import HomeIntroduction from "./components/HomeIntroduction.vue";

export default {
  components: {
    HeaderComponent,
    HomeIntroduction,
    FeaturesComponent,
  },
};
</script>

<style>
body {
  margin: 0;
  padding: 0;
}

#introduction {
  top: 0;
  left: 0;
  background-image: url('assets/images/blue_bg.png');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: top;
}
</style>
