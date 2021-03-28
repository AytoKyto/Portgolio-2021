<template>
  <div class="wrapperMainChoix">
    <div class="wrapperInfoChoix">
        <p @click="test" class="subInfoChoix subInfoChoixTitle">Merch</p>
      <div class="wrapperTextInfoChoix" v-if="type === 1">
        <p class="subInfoChoix subInfoChoixTitle">Merch</p>
        <p class="subInfoChoix">Decouvez mes visuelles</p>
        <img class="imgInfoChoix" src="../img/photo-merch.png" alt="" />
      </div>
      <div class="wrapperTextInfoChoix" v-else-if="type === 2">
        <p class="subInfoChoix subInfoChoixTitle">test</p>
        <p class="subInfoChoix">Decouvez mes visuelles</p>
        <img class="imgInfoChoix" src="../img/photo-merch.png" alt="" />
      </div>
      <div class="wrapperTextInfoChoix" v-else>
        <p class="subInfoChoix subInfoChoixTitle">Web</p>
        <p class="subInfoChoix">Decouvez mes visuelles</p>
        <img class="imgInfoChoix" src="../img/photo-merch.png" alt="" />
      </div>
      
    </div>
    <MenuBurger />
    <ChoixSolaire />
  </div>
</template>

<script>
let type = 1;
export default {
  data: {
        type:1,
    },
  methods: {
    test() {
      console.log(type); 
    },
  },
};
</script>

<style>
body {
  background-color: #000000;
  margin: 0;
}
.subInfoChoixTitle {
  margin-left: 2vw;
  font-size: 3vw;
}
.titleChoix {
  color: #ff5c00;
  position: absolute;
  top: -2vw;
  left: 2vw;
  font-size: 3vw;
}
.imgInfo {
  height: 47vw;
  margin-left: -10vw;
}
.imgInfoChoix {
  position: absolute;
  width: 30vw;
  top: 23vw;
  left: -8vw;
}
.wrapperMainChoix {
  background-image: url(../img/wall-choix.png);
  background-size: cover;
  cursor: url(../img/cur.svg), auto;
}
.wrapperTextInfoChoix {
  color: rgb(93 100 55);
  position: absolute;
  top: 7.5vw;
  font-size: 2vw;
  transform: rotate(-12deg);
}
.wrapperMainFlex {
  display: flex;
  justify-content: space-between;
  overflow: hidden;
}
.wrapperLink {
  position: absolute;
  top: 40vw;
}
.wrapperInfoChoix {
  position: absolute;
  top: 0vw;
  left: 0vw;
  overflow: hidden;
  width: 30vw;
  height: 100vh;
}
</style>
