<template>
  <div class="element-home-wrapper">
    <div class="element-home-container">
      <div class="element-content-column">
        <HomeContent />
        <ButtonComponent />
      </div>
    </div>
  </div>
</template>

<script>
import HomeContent from "@/components/HomeContent";
import ButtonComponent from "@/components/ButtonComponent";
export default {
  components: { HomeContent, ButtonComponent },
};
</script>

<style scoped>
.element-home-wrapper {
  background-image: url(https://ting.global/wp-content/uploads/2021/04/sliderx.jpg);
  height: 872px;
}
.element-home-container {
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.element-content-column {
  display: flex;
  flex-direction: column;
  justify-content: center;
  /* height: 872px; */
}
</style>
