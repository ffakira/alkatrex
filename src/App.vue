<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/custom.png">
    <HelloWorld msg="Alkatrex being launched 2020!"/>

    <h3>Be social! Follow us: </h3>
    <i class="fa fa-md fa-facebook" > <a target="_blank" rel="noopener noreferrer" href="https://www.facebook.com/alkatrex">Alkatrex</a></i>
    <i class="fa fa-md fa-instagram"> <a target="_blank" rel="noopener noreferrer" href="https://www.instagram.com/AlkatrexOfficial">AlkatrexOfficial</a></i>
    <i class="fa fa-md fa-twitter"> <a target="_blank" rel="noopener noreferrer" href="https://www.twitter.com/alkatrex">Alkatrex</a></i>
    <i class="fa fa-md fa-youtube"> <a target="_blank" rel="noopener noreferrer" href="https://www.youtube.com/channel/UCGB5oOXchKWd2rMFz6aMOSg">Alkatrex</a></i>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

a {
  margin-left: 3px;
  text-decoration: underline;
  color: black;
}

i {
  margin: 0 10px;
}

img {
  width: 400px;
}
</style>
