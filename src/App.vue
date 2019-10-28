<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.nav-bar{
  padding: 10px;
  background-color: #a3c7c4;
  list-style: none;
  margin-top:100px
}

.logo{
  float: left;
  vertical-align: top;
  height: 100px;
  margin-top: -100px
}

#dress{
    float: left;
    margin-top: 50px;
    font-size: 30px;
    margin-left: -84px;
}

.product-dress{
    text-align: left;
    margin-left: -130px;
    font-size: 6px;
    margin-top: 34px
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
