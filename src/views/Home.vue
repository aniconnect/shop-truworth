<template>
  <div class="home">
    <div>
    <img class="logo" alt="Truworth Logo" src="../assets/South-Africas-Truworths-in-talks-about-462M-bid-for-British-footwear-r....jpg" align="left">
    </div>
    <div class="nav-bar">
    <strong><h1>Shop Truworth - Female Dress</h1></strong>
  </div>
  <div class="product">
  <div class="product-image">
    <img class="product-dress" alt="Ladies Party Dress" src="../assets/61Fjkhz99CL._SR500,500_.jpg" align="left">
     <div class="product-info">
        <strong><p id="dress">{{product}}</p></strong>
  </div>
  </div>
  </div>
  </div>
</template>

<script>
export default {
  data(){
    return {
      product : "Party dress",
    }
  }
}
</script>
