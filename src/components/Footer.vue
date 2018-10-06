<template>
  <div class="container">
    <div class="menu">
      <a href="https://www.gitshowcase.com/krystianjonca" target="_blank" rel="noopener"><strong>Portfolio</strong></a>
      <a href="https://github.com/KrystianJonca" target="_blank" rel="noopener"><strong>Github</strong></a>
      <a href="" target="_blank" rel="noopener"><strong>Twitter</strong></a>
      <a href="https://www.buymeacoffee.com/wionek" target="_blank" rel="noopener"><strong>BMAC</strong></a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style lang="less" scoped>
.container{
  border-top: 1px solid #FFFFFF;
  padding-top: 15px;
  .menu{
    padding-top: 15px;
    position: absolute;
    left: 50%;
    transform: translateX(-50%) translateY(-50%);
    a {
      margin: 25px;
      text-decoration: none;
      color: #FFFFFF;
      @media (max-width: 481px) { margin: 8px; }
    }
  }
}
</style>
