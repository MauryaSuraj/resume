<template lang="html">
  <div class="bg">
    <div class="container">
      <div class="row mt-5 pt-5">
        <div class="col-md-6 m-auto p-auto">
            <h1 class="heading-top">
              Suraj Maurya
            </h1>
            <h5 class="heading-below my-3">
              Full Stack Developer
            </h5>
            <ul>
              <li> <i class="far fa-envelope mr-2"></i> surajmaurya450@gmail.com  </li>
              <li> <i class="fas fa-map-marker-alt mr-2"></i> New Delhi, Delhi india - 110080 </li>
              <li> <i class="fas fa-phone mr-2"></i> +91 8375980653, +91 8851951226</li>
            </ul>
        </div>
        <div class="col-md-6">

        </div>
      </div>
      <div class="row mt-5 pt-4">
        <i class="fab fa-facebook-f fa-2x mr-5"></i>
        <i class="fab fa-linkedin-in fa-2x mr-5"></i>
        <i class="fab fa-github fa-2x mr-5"></i>
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
  margin-bottom: 1rem;
  font-weight: 400;

}
.bg{
  background-image: linear-gradient(to bottom, black, #212121ab ), url('../../assets/bg.jpg');
  height: 100vh;
  width: 100%;
  background-size: cover;
  background-position: center;
}
.green{
  background-color: green;
  color: white;
  width: auto;
  padding: 1rem;
}
.heading-top{
  font-weight: 900;
  font-size: 5rem;
}
</style>
