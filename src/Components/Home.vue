<template>
  <div class="home">
    <div class="mainDiv">
      <p>Welcome to <br><span style="margin:0%;"> Web Design</span></p>
      <img align="right" src="../Assets/Capture.png">
    </div>
    <p>It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English.</p>
  </div>
</template>
<script>
export default {
  data() {
    return {
    };
  }
};
</script>
<style>
.home{
    width: 80%;
    height: 100px;
    background-color: rgb(248, 246, 246);
    position: relative;
    margin:5%;
    animation-name: example;
    animation-duration: 2s;
    animation-iteration-count: 1
}
@keyframes example {
    0%   {background-color:#fdfdfd ;left:0px; top:0px;}
    25%  {background-color:#ffffff; left:200px; top:50px;}
    100% {background-color:#ffffff; left:0px; top:0px;}
}
.mainDiv{
  width: 100%;
  position: relative;
}
.mainDiv img{
  position: relative;
  margin-top: 5%;
  
}
.mainDiv >p{
  font-size: 7vw;
  text-shadow: #a8a7a7 2px 10px;
  font-weight: bolder;
  width: 45%;
  float: left;
}
span{
  color:rgb(73, 95, 165);
}
.home >p{
  color:rgb(26, 26, 26);
  position: relative;
  float:left;
  width: 40%;
  margin-top: 10%;
  font-size: 1.2vw;
  font-style: oblique;
}
</style>