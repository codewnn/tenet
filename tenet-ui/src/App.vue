<template>
    <div id="app">
        <router-view></router-view>
<!--        "circle","edge","triangle", "polygon","star"-->
<!--        <vue-particles-->
<!--                color="#fff"-->
<!--                :particleOpacity="0.7"-->
<!--                :particlesNumber="60"-->
<!--                shapeType="circle"-->
<!--                :particleSize="2"-->
<!--                linesColor="#fff"-->
<!--                :linesWidth="0.8"-->
<!--                :lineLinked="true"-->
<!--                :lineOpacity="0.4"-->
<!--                :linesDistance="150"-->
<!--                :moveSpeed="2"-->
<!--                :hoverEffect="true"-->
<!--                hoverMode="grab"-->
<!--                :clickEffect="true"-->
<!--                clickMode="push"-->
<!--                class="lizi"-->
<!--        >-->
<!--        </vue-particles>-->
    </div>
</template>
<style>
  *{
    margin: 0px;
    padding: 0px;
  }
  ul{
    list-style: none;
  }
  html,body,#app{
      height: 100%;
  }
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
    height: 100%;
    /*background-color: cadetblue;*/
}
  #particles-js{
      top: 0px;
      width: 100%;
      height: 100%;
      position: absolute;
      background-color: cadetblue;
      z-index: -5;
  }

</style>
