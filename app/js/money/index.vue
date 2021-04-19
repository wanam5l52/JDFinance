<template lang="html">
    <div>
        <Heador></Heador>
        <Slider></Slider>
        <Ada></Ada>
        <Money></Money>
        <Adb></Adb>
        <Finance></Finance>
        <Adc></Adc>
        <Footor cname="mfooter"></Footor>
        <Navbar></Navbar>
    </div>
</template>

<script>
import Heador from "../public/header.vue";
import Navbar from "../public/navbar.vue";
import Slider from "./mslider.vue";
import Ada from "./ada.vue";
import Adb from "./adb.vue";
import Finance from "./finance.vue";
import Money from "./money.vue";
import Footor from "../public/footer.vue";
import Adc from "./adc.vue";
export default {
  components: {
    Heador,
    Navbar,
    Slider,
    Ada,
    Adb,
    Money,
    Finance,
    Footor,
    Adc,
  }
}
</script>

<style lang="scss">
.mfooter {
  margin-top: 0!important;
  ul {
    li:first-child {
      display: none;
    }
  }
}

</style>
