<template>
  <div id="app" class="container">
    
    <my />
    <img alt="Vue logo" src="./assets/im.jpg" />
    <div class="centered">"The most Successfull Event is the One that achieves your Goals and Exceeds your Expectations"</div>
  <next />
  </div>


</template>
<script>
import my from "./components/my.vue";
import next from "./components/next.vue";
export default {
  name: "app",
  components: {
    my,
    next
   
  }
};

</script>
<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
img{
  width:100%
}
/* .container {
  position: relative;
  text-align: center;
  color: white;
} */
.centered {
  position: absolute;
  top: 90%;
  margin-left: 50%;
text-align: center;
  transform: translate(-50%, -50%);
  font-size: 50px;
  color:black;
  font-family:serif;
  background: rgba(0, 103, 151, 0.3); 
  margin-top:20%
}

/* Add a black background color to the top navigation bar */


</style>
