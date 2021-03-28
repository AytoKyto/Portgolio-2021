<template>
  <div class="wrapper-main">
    <div class="wrapper-main-flex wrapperMainFlexOne">
      <SideBar />
    </div>
    <div class="wrapper-main-flex wrapperMainFlexTwo">
      <NameHeader />
      <MenuBurger />
      <div class="wrapperChoix">
        <div class="wrapperImgOne">
          <WebOrangeOne />
          <div class="imgAnim">
            <img src="../img/web.jpg" alt="image web" />
          </div>
          <WebOrangeTwo />
        </div>
        <div class="wrapperImgTwo">
          <NuxtLink class="a" to="/merch">
            <div class="wrapperTitleOrangeMerch">
              <p class="pMerch">MERCH</p>
            </div>
            <div class="imgAnim">
              <img src="../img/hoodie.jpg" alt="image hoodie" />
            </div>
          </NuxtLink>
        </div>
      </div>
    </div>
    <div id="menuOpen">
      <AllMenu />
    </div>
    <div class="wallStart">
      <img src="../img/star.png" alt="wall" />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
body {
  background-color: #000000;
  margin: 0;
}
.wrapper-main {
  overflow: hidden;
}
.wallStart {
  position: absolute;
  z-index: -999;
  overflow: hidden;
  width: 100vw;
  height: 100vh;
}
.wrapperImgOne img,
.wrapperImgTwo img {
  opacity: 70%;
}
.wrapperImgOne img:hover,
.wrapperImgTwo img:hover {
  opacity: 100%;
}
.wrapperChoix {
  display: flex;
  justify-content: space-between;
  padding-left: 7vw;
  margin-top: 3vw;
  width: 90%;
}
.wrapperTitleOrangeMerch {
  position: relative;
  margin-bottom: -14vw;
  z-index: 999;
}
.pMerch {
  color: black;
  background-color: #ff5c00;
  padding: 2vw;
  margin-left: -2vw;
  font-size: 3vw;
  width: 16vw;
}
.a {
  text-decoration: none;
}
.wrapperImgTwo {
  margin-right: 5vw;
  margin-top: -1vw;
}
.webOrangeOne {
  position: relative;
  margin-bottom: -4vw;
  margin-left: -2vw;
}
.webOrangeTwo {
  position: relative;
  margin-top: -6vw;
  margin-left: -5vw;
}
#menuOpen {
  display: none;
}
.bigWrapperSaturne {
  position: absolute;
  z-index: -999;
  margin: 0 auto;
  margin-top: 4vw;
}
.wrapper-main {
  display: flex;
  justify-content: space-around;
}
.wrapperMainFlexOne {
  width: 5vw;
  height: 100vh;
}
.wrapperMainFlexTwo {
  width: 95vw;
  height: 100vh;
}
.h1Index {
  color: #ff5c00;
  font-size: 9vw;
  margin-top: 8vw;
  margin-left: 3vw;
  line-height: 1;
}
.pIndex {
  color: #ff5c00;
  margin-left: 3vw;
  padding-left: 1.5vw;
  border-left: 3px dotted #ff5c00;
  width: 30vw;
  height: 6vw;
  font-size: 0.85vw;
}
.wrapperSvgFooter {
  position: absolute;
  margin-left: 45vw;
  bottom: 1vw;
}
.wrapperRightSvg {
  position: absolute;
  right: 1vw;
  margin-top: 1vw;
}

/*---------------------------
----------annimation---------
-----------------------------*/
.wallStart img {
  position: relative;
  animation: rotateSat 15s linear infinite;
}
/*#Rectangle_33 {
  position: relative;
  animation: trans1 15s linear infinite;
}*/
@keyframes rotateSat {
  from {
    bottom: 0px;
  }
  to {
    bottom: 200px;
  }
}
@keyframes trans1 {
  from {
    width: 0px;
  }
  to {
    width: 200px;
  }
}
#Rectangle_33,
#Rectangle_34,
#Rectangle_38,
#Rectangle_36,
#Rectangle_37 {
  position: relative;
  animation: anim 4s;
}
@keyframes anim {
  from {
    width: 0%;
  }
  to {
    width: 250px;
  }
}
.imgAnim {
  position: relative;
  overflow: hidden;
  width: 100%;
  height: 100%;
  animation: imga 4s;
}
@keyframes imga {
  from {
    width: 0%;
  }
  to {
    width: 100%;
  }
}
</style>
