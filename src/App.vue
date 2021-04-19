<template>
  <div id="app">
    <Home />
    <FounderAndConfirmation />
    <Eat />
    <Drink />
    <Bookings />
    <FooterArea />
  </div>
</template>

<script>
import Home from "./components/Home/Home";
import FounderAndConfirmation from "./components/FounderAndConfirmation/FounderAndConfirmation";
import Eat from "./components/Eat/Eat";
import Drink from "./components/Drink/Drink";
import Bookings from "./components/Bookings/Bookings";
import FooterArea from "./components/FooterArea/FooterArea";
export default {
  name: 'App',
  components: {
    Home,
    FounderAndConfirmation,
    Eat,
    Drink,
    Bookings,
    FooterArea,
  },
};
</script>

<style>
body {
  background-color: #EDECEA;
  color: #163A28;
  font-family: elina01;
}

</style>
