<template>

  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <div>
    <!-- <div>
      <Header/>
    </div> -->
    <div>
      <LeftMenu/>
    </div>
    <div>
      <banner></banner>
    </div>
    <div>
      <MainContent/>
    </div>
    <!-- <div>
      <Footer/>
    </div> -->
  </div>
  
</template>

<script>

//import Header from './components/Header.vue';
import LeftMenu from './components/LeftMenu.vue';
import Banner from './components/Banner.vue';
import MainContent from './components/maincontent/MainContent.vue';
//import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    //Header,
    LeftMenu,
    Banner,
    MainContent,
    //Footer
  },
  mounted() {
    let jqueryScript = document.createElement('script');
    jqueryScript.setAttribute("src","https://code.jquery.com/jquery-3.3.1.slim.min.js");
    document.head.appendChild(jqueryScript);

    let ajaxScript = document.createElement('script');
    ajaxScript.setAttribute("src","https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js");
    document.head.appendChild(ajaxScript);

    let bootrstrapScript = document.createElement('script');
    bootrstrapScript.setAttribute("src","https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js");
    document.head.appendChild(bootrstrapScript);
  }
}

</script>


<style>

@import './assets/styles/normalize.css';
@import './assets/styles/font-awesome.css';
@import 'https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css';
@import './assets/styles/style.css';
@import './assets/styles/bootstrap.min.css';

/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
} */
</style>
