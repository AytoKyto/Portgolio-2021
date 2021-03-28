<template>
<div class="navDesktop">
        <div class="nameSiteHeader">
          <div class="nameHeaderLeft">
            <p class="nameLeftCesi pNameNav">CESI</p>
            <p class="nameLeftAlter pNameNav">Alternance</p>
          </div>
          <div class="nameSiteNavBig">
            <div class="nameSitePrimaryFlex">
              <p class="nameSiteNavPrimary nameSiteNavPrimaryOne pNameNav">MATHIS</p>
              <p class="nameSiteNavPrimary nameSiteNavPrimaryTwo pNameNav">FLEURY</p>
            </div>
            <p class="nameSiteNavDev pNameNav">DEVELOPPEUR</p>
            <div class="nameSiteSecondFlex">
              <p class="nameSiteNavSecond pNameNav">WEB</p>
              <p class="nameSiteNavSecond pNameNav">PORTFOLIO</p>
            </div>
          </div>
          <div class="nameSiteNavSvg">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="29.5"
              height="35.5"
              viewBox="0 0 29.5 35.5"
            >
              <g
                id="Groupe_26"
                data-name="Groupe 26"
                transform="translate(-1077.5 -22.5)"
              >
                <line
                  id="Ligne_15"
                  data-name="Ligne 15"
                  y2="34.5"
                  transform="translate(1082.5 23.5)"
                  fill="none"
                  stroke="#ff5c00"
                  stroke-width="1"
                />
                <line
                  id="Ligne_16"
                  data-name="Ligne 16"
                  y2="10"
                  transform="translate(1087.5 23) rotate(90)"
                  fill="none"
                  stroke="#ff5c00"
                  stroke-width="1"
                />
                <line
                  id="Ligne_14"
                  data-name="Ligne 14"
                  y2="10"
                  transform="translate(1087.5 57.5) rotate(90)"
                  fill="none"
                  stroke="#ff5c00"
                  stroke-width="1"
                />
                <text
                  id="_40"
                  data-name="40"
                  transform="translate(1092 44)"
                  fill="#ff5c00"
                  font-size="11"
                  font-family="LW, Linowrite"
                >
                  <tspan x="0" y="0">40</tspan>
                </text>
                <line
                  id="Ligne_18"
                  data-name="Ligne 18"
                  y2="5"
                  transform="translate(1087 40.303) rotate(90)"
                  fill="none"
                  stroke="#ff5c00"
                  stroke-width="1"
                />
              </g>
            </svg>
          </div>
        </div>
      </div>
</template>

<style>

/*_______________________________________
_______________ Nav _____________________*/

.nameSiteHeader {
  color: #ff5c00;
  display: flex;
  justify-content: center;
  margin-top: 1vw;
  font-size: 0.61vw;
}
.pNameNav {
  margin: 0vw;
  padding: 0vw;
}
.nameHeaderLeft,
.nameSitePrimaryFlex {
  display: flex;
  justify-content: center;
  text-align: center;
}
.nameHeaderLeft p {
  writing-mode: vertical-rl;
  text-orientation: mixed;
}
.nameSiteNavBig {
  display: flex;
  flex-direction: column;
  width: 6vw;
}
.nameHeaderLeft {
  margin: 0.1vw;
}
.nameLeftCesi {
  font-size: 0.7vw;
}
.nameLeftAlter {
  font-size: 0.35vw;
}
.nameSiteSecondFlex {
  display: flex;
  justify-content: space-between;
}
.nameSiteNavPrimary {
  font-size: 0.72vw;
  padding: 0.045vw;
}
.nameSiteNavPrimaryOne {
  padding-left: 0;
}
.nameSiteNavPrimaryTwo {
  padding-right: 0;
}
.nameSiteNavBig {
  padding-left: 0.1vw;
  padding-right: 0.1vw;
}
</style>
