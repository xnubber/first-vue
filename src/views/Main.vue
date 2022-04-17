<template>
  <div class="wrapper">
    <Navbar />
    <div class="two">
      Data
      <div class="two-a">
        <div class="block">block</div>
        <div class="block">block</div>
        <div class="block">block</div>
        <div class="block">block</div>
      </div>
      <div class="two-b">block</div>
      <div class="two-c">block</div>
    </div>
  </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'
  export default {
    components: {
      Navbar
    }
  }
</script>


<style>
.wrapper {
  margin: 0 auto;
  overflow: hidden;
  display: flex;
  justify-content: center;
}

*,
*:before,
*:after {
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
}

body {
  background: #fff;
  color: #fff;
  font-family: "Open Sans";
  font-size: 40px;
  font-weight: 700;
  text-align: center;
  margin: 0;
}

.one,
.two,
.two-a,
.two-b,
.two-c,
.three,
.block {
  border: 2px solid;
  box-sizing: border-box;
}

.one,
.two,
.three {
  padding: 20px;
  background-color: #163a59;
  color: #ff6600;
}

.two-a,
.two-b,
.two-c {
  padding: 15px;
  font-size: 30px;
  margin: 10px;
  background-color: #36c1ce;
  color: #fff;
}

.two-a {
  min-height: 200px;
  padding: 0;
}

.block {
  padding: 40px;
  font-size: 20px;
  background-color: #ff6600;
  color: #163a59;
}

.one {
  width: 15%;
  height: 100vh;
  display: flex;
  flex-direction: column;
}

.two {
  width: 85%;
}

.link {
  color: #fff;
  text-decoration: none;
  margin: auto;
  text-align: center;
}
</style>