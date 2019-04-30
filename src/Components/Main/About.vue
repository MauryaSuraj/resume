<template lang="html">
  <div class="row">
    <div class="col-md-6">
      <img src="../../assets/bgbig.png" alt="">
    </div>
    <div class="col-md-6">
      <div class="bg z-depth-3 p-3">
        <h2 class="h1  text-uppercase"> About Me </h2>
        <p> Hello, I’m a Patrick, web-developer based on Paris. I have rich experience in web site design & building and customization. Also I am good at </p>
        <ul>
          <li> <span>PHP</span> </li>
          <li> <span>HTML</span> </li>
          <li> <span>CSS</span> </li>
          <li> <span>WORDPRESS</span> </li>
          <li> <span>VUE</span> </li>
          <li> <span>JAVASCRIPT</span> </li>
          <li> <span>MYSQL</span> </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="css" scoped>
  li{
    list-style-type: none;
    margin: 0px 6px;
    border-radius: 4px;
    margin-bottom: 10px;
    padding: 4px 0px;
    display: inline-block;
  }
  ul li span{
    border: 1px solid #0bceaf;
    padding: 4px 10px;
    border-radius: 4px;
    color: white;
  }
  .bg{
    background-color: #111111;
  }
  .z-depth-3 {
    -webkit-box-shadow: 0 12px 15px 0 rgba(0, 0, 0, .24), 0 17px 50px 0 rgba(0, 0, 0, .19) !important;
    box-shadow: 0 12px 15px 0 rgba(0, 0, 0, .24), 0 17px 50px 0 rgba(0, 0, 0, .19) !important
}
</style>
