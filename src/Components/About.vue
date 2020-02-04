<template>
    <div>
    <p style="font-size:3vw;color:blue;">Hello From about</p>
    </div>
</template>
<style  scoped>

div{
    width: 80%;
    height: 100px;
    background-color: red;
    position: relative;
    margin:5%;
    animation-name: example;
    animation-duration: 2s;
    animation-iteration-count: 1
}
@keyframes example {
    0%   {background-color:red; left:0px; top:0px;}
    25%  {background-color:yellow; left:200px; top:50px;}
    100% {background-color:red; left:0px; top:0px;}
}
</style>