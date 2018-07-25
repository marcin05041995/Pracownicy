<template>
  <div id="app">
    <img src="./assets/pracownik.jpg">
    <Worker/>
    <AddWorker/>
  </div>



</template>

<script>
import Worker from './components/Worker'
import AddWorker from './components/AddWorker'


export default {
  name: 'App',
  components: {
    Worker,AddWorker
  }
}
</script>

<style>

template{
  background-color: #2c3e50;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}


#app>img{
  width:300px;
  height:300;
  float:left;
  margin-left:100px;
}
</style>
