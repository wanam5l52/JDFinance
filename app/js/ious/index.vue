<template lang="html">
    <div>
        <Heador></Heador>
        <Slider></Slider>
        <Welfare></Welfare>
        <Service></Service>
        <Footor></Footor>
        <Navbar></Navbar>
    </div>
</template>

<script>
import Heador from "../public/header.vue";
import Navbar from "../public/navbar.vue";
import Footor from "../public/footer.vue";
import Slider from "./islider.vue";
import Welfare from "./welfare.vue";
import Service from "./service.vue";
export default {
  components: {
    Heador,
    Navbar,
    Footor,
    Slider,
    Welfare,
    Service,
  }
}
</script>

<style lang="scss">


</style>
