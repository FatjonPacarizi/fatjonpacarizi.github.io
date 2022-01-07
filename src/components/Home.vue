<template>
    <div id="home">
        <div class="home-backgound text-white p-5 align-">
            <div class="row">
                <div class="col col-sm-6 rounded" style="background-color: rgb(0,0,0,0.2)">
                    <h1>Lorem ipsum dolor sit amet</h1>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. In, cumque porro. Ex blanditiis aperiam quasi molestiae debitis, cumque mollitia nobis enim iure nam facere ipsam beatae dignissimos placeat ullam qui!</p>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. In, cumque porro. Ex blanditiis aperiam quasi molestiae debitis, cumque mollitia nobis enim iure nam facere ipsam beatae dignissimos placeat ullam qui!</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .home-backgound{
        background-image: url("../assets/home.jpg");
        background-repeat: no-repeat;
        background-size: cover;
        min-height: 100vh;
        display: flex;
        align-items: center;
    }
    #home{
        padding-top: 56px;
    }
</style>
