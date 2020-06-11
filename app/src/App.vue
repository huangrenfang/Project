<template>
  <div id="app">
    <Title></Title>
    <Head></Head>
    <Nav></Nav>
    <router-view/>
  </div>
</template>

<script>
import Title from './components/Title';
import Head from './components/Head';
import Nav from './components/Nav';
export default {
  components: {
    Title,
    Head,
    Nav
  }
}
</script>

<style lang="scss">
  body{
    margin: 0;
    padding: 0;
  }
</style>
