<template>
  <div id="app">
    <Header></Header>
    <RightCol></RightCol>
    <LeftCol></LeftCol>
    <!-- <img alt="Vue logo" src="./assets/logo.png" width="25%" /> -->
    <!-- <HelloWorld msg="test Vue in CodeSandbox!" /> -->
    <Footer></Footer>
  </div>
</template>



<script>
//import HelloWorld from "./components/HelloWorld";
import Footer from "./components/Footer";
import Header from "./components/Header";
import RightCol from "./components/RightCol";
import LeftCol from "./components/LeftCol";

export default {
  name: "App",
  components: {
    Footer,
    Header,
    RightCol,
    LeftCol,
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
