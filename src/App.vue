<template>
  <nav class="p-0">
 <Navbar></Navbar>
  </nav>
  <body>

    <router-view/>
  </body>
  <footer>
<Footer></Footer>
  </footer>
</template>
<script>
import Navbar from './components/NavbarPort.vue';
import Footer from './components/FooterPort.vue';
  export default {
    components: {
    Navbar,
    Footer
},
  }
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Archivo+Narrow&family=Barlow+Semi+Condensed:ital,wght@1,200&family=Comfortaa&family=Golos+Text:wght@400;500&family=News+Cycle:wght@700&family=Poppins:ital,wght@0,200;0,300;1,300&family=Roboto:ital,wght@0,300;0,400;0,500;1,100;1,500&family=Varela+Round&display=swap');
#app {
  font-family: 'Archivo Narrow', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #eee9e9;
}
body{
  min-height: 100vh; 
  overflow-x: hidden;

}
footer{
  margin-top: auto;
}

nav {
  padding: 30px;
  
}

nav a {
  font-weight: bold;
  color: #bac9ff;
}

nav a.router-link-exact-active {
  color: rgb(255, 255, 255);
}
</style>
