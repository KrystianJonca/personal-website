<template>
  <div id="app">
    <Header />
  </div>
</template>

<script>
import Header from './components/Header'

export default {
  name: 'app',
  components: {
    Header
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
  width: 50%;
  @media (max-width: 1025px) { width: 75% }
  @media (max-width: 767px) { width: 100% }
}
</style>
