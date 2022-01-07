<template>
    <div id="contactus">
      <div class="container">
        <div class="row pt-5">
          <div class="col-sm-12 col-md-6 col-lg mb-3">
            <ul>
              <li class="pb-3"><img src="../assets/logo.png" alt=""></li>
              <li>Lorem ipsum dolor sit amet consectetur</li>
            </ul>
          </div>
          <div class="col-sm-12 col-md-6 col-lg mb-3">
            <ul>
              <h5 class="pb-3">Information</h5>
              <li>
                Home
              </li>
              <li>
                About Us
              </li>
              <li>
                Service
              </li>
              <li>
                Contanct Us
              </li>
            </ul>
          </div>
          <div class="col-sm-12 col-md-6 col-lg mb-3">
            <ul>
              <h5 class="pb-3">About Us</h5>
              <li>
                Home
              </li>
              <li>
                About Us
              </li>
              <li>
                Service
              </li>
              <li>
                Contanct Us
              </li>
            </ul>
          </div>
          <div class="col-sm-12 col-md-6 col-lg mb-3">
            <ul>
              <h5 class="pb-3">Quick Links</h5>
              <a href="tel:+0123456789"><li><p class="h5 mb-2"><b-icon icon="telephone"></b-icon><span class="pl-2">  +0123456789</span></p></li></a>
              <a href="mailto:example@gmail.com"><li><p class="h5 mb-2"><b-icon icon="envelope"></b-icon><span class="pl-2">  example@gmail.com</span></p></li></a>
              <li><p class="h5 mb-2"><b-icon icon="house"></b-icon><span class="pl-2">  1234 example example</span></p></li>
            </ul>
          </div>
        </div>
      </div>
      <hr>
      <div class="text-center copyright p-1">
        <p>&copy; 2021</p>
      </div>
    </div>
</template>

<script>
export default {
  name: 'Footer',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  #contactus{
    background-color: #1A4D8C;
    color: white;
  }
  ul{
    list-style-type: none;
  }
  li{
    margin-bottom: 15px;
  }
  .copyright{
    text-align: center;
  }
  a{
    text-decoration: none;
    color: white;
  }
  a:hover{
    color: white;
  }
  img{
    height: 50px;
    width: 50px;
  }
</style>