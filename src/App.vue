<template>
  <div id="app">
    <nav>
      <img class="logo" src="./Assets/logo.png">
      <div class="language">
        <a> Language </a>
        <img style="width:10%;margin-top:2%" src="./Assets/strelica.png">
     
      </div>
      <ul>
        <li><router-link to="/">Home </router-link></li>
        <li><router-link to="/portofolio">Projects </router-link></li>
        <li><router-link to="/about">About us  </router-link></li>
        <li><router-link to="/blog">Blog  </router-link></li>
        <li><router-link to="/contact"> Contact </router-link></li>
      </ul>
    </nav>
    
    <router-view></router-view>
    <footer>
    <h5 style="opacity:60%;margin-top:0.6%;">Copyrights Kenan and Antonija Design</h5>
    </footer>
  </div>
</template>

<script>
export default {
  name: "app",
  data() {
    return {};
  }
};
</script>

<style>
*{
  margin:0;
}
nav{
  border: 0px solid;
  padding: 1px;
box-shadow: 5px 2px 31px 1px #bbbbbb;
}
.logo{
  position:absolute;
  width: 10%;
  height: 9%;
  margin: 0%;
  text-align: center;
  margin-top:0.5%;
  margin-left: 2%;
}

.language{
  position: absolute;
  height: 20px;
  margin: 1%;
  margin-left: 89%;
  padding: 10px;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
font-size: 1.5vw;
}
a:hover{
  color:#1164b0;
}

ul{
  text-align: center;
  position: relative;
}
ul li{
  display: inline-block;
  list-style-type: none;
  margin: 2% 1%;
}
ul li a{
  text-decoration: none;
  font-size: 1.5vw;
  color:black;
 font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;

}
ul li a:hover{
color:#1164b0;
}
footer{
  width: 100%;
  background-color: #bdbcbc;
  height: 40px;
  text-align: center;
  position: relative;
  position: fixed;
  padding: 10px;
  bottom:0;
}

</style>
