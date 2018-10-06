<template>
  <div id="app">
    <Header />
    <Main />
  </div>
</template>

<script>
import Header from './components/Header'
import Main from './components/Main'

export default {
  name: 'app',
  components: {
    Header,
    Main
  }
}
</script>

<style lang="less">
body{
  font-family: 'Open Sans', sans-serif;
  background-color: #212121;
  height: 100%;
  color: #FFFFFF;
}
.container{
  margin: auto;
  width: 40%;
  @media (max-width: 1025px) { width: 75% }
  @media (max-width: 767px) { width: 100% }
}
p{
  color: #E0E0E0;
}

</style>
