<template>
  <navbar-comp/>
  <router-view/>
  <!-- <spinner/> -->
  <footer-comp/>
</template>

<script>
// import Spinner from './components/Spinner.vue';
import NavbarComp from './components/NavbarComp.vue';
import FooterComp from './components/FooterComp.vue';


export default {
  components: {
    NavbarComp,
    FooterComp,
    // Spinner,
  }
}


</script>


<style>

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #eee6e6;
  /* padding-bottom: 70%; */
  /* background-image: url('https://i.ibb.co/2qV7YLd/wp4006828.jpg'); */
  
  
  
}

nav {
  padding: 30px;
}

nav a {

  font-weight: bold;
  color: #ede6e6;
}

nav a.router-link-exact-active {
  border: solid 1px black;
  padding: 5px;
  color: #070808;
  background-color: #ede6e6;
  border-radius: 5px 5px 5px 0;
  /* box-shadow: #eee6e6 2px; */
  box-shadow: 1px 1px 5px rgb(6, 2, 2);
  transition: transform .9s;
  /* transition: ease-in; */
}
nav a.router-link-exact-active:hover {
  transform: scale(1.2); 
}
</style>
