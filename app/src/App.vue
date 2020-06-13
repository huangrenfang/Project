<template>
  <div id="app">
    <Title></Title>
    <Head></Head>
    <Nav></Nav>
    <Footer></Footer>
    <router-view/>
    
  </div>
</template>

<script>
import Title from './components/Title';
import Head from './components/Head';
import Nav from './components/Nav';
import Footer from './components/Footer';
// import Home from './views/Home';
export default {
  components: {
    Title,
    Head,
    Nav,
    Footer,
    // Home
  }
}
</script>

<style lang="scss">
  #app{
    display: flex;
    flex-direction: column;
  }
  body{
    margin: 0;
    padding: 0;
  }
  #footer{
    position: absolute;
    bottom: -4000px;
    z-index: 22;
  }
</style>
