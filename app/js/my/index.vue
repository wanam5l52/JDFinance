<template lang="html">
    <div>
        <Heador></Heador>
        <Myname></Myname>
        <Mylist></Mylist>
        <Navbar></Navbar>
    </div>
</template>

<script>
import Heador from "../public/header.vue";
import Navbar from "../public/navbar.vue";
import Mylist from "./mylist.vue";
import Myname from "./myname.vue";
export default {
  components: {
    Heador,
    Navbar,
    Mylist,
    Myname,
  }
}
</script>

<style lang="scss">


</style>
