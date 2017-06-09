<template lang="html">
  <footer>
    <p style="border-top:1px solid #ccc">我祈祷拥有一颗透明的心灵和会流泪的眼睛</p>
  </footer>
</template>

<script>
export default {
}
</script>

<style lang="css" scoped>
  footer{
    height: 10rem;
    text-align: center;
    display: flex;
    display: -webkit-flex;
  }
  footer p{
    margin:auto;
    font-size: 1.4rem;
    color: #3d3d3d;
    padding: 1rem 1.5rem;
  }
  @media screen and (max-width:768px){
    footer{
      height: 6rem;
    }
  }
</style>
