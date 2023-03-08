<template>

<div id="options">
 <div id="main" class="mn" v-if="mainOpt === true">
  <div @click="OptionsAccesories = true; mainOpt = false">
    <svg viewBox="0 0 220 220">
      <g id="a_earphones">
        <path fill="#b9b9b9" d="M31 60c1,-2 2,-3 4,-3l4 0c2,0 3,1 3,3l0 10c0,2 -1,4 -3,4l-4 0c-2,0 -3,-2 -4,-4l0 7c0,0 0,1 -1,1l0 0c0,15 10,28 25,46 4,4 7,8 11,13 5,6 10,10 14,13 7,6 13,10 17,22 1,4 1,8 1,14 0,6 -1,13 1,20 2,11 3,25 3,39 0,7 1,15 1,21l0 1 -2 0 0 -1c-1,-6 -1,-14 -1,-21 -1,-14 -1,-28 -3,-38 -2,-7 -2,-15 -1,-21 0,-5 0,-10 -1,-13 -4,-11 -10,-16 -16,-21 -5,-3 -10,-7 -15,-13 -3,-5 -7,-9 -10,-13 -16,-19 -27,-32 -27,-48l0 0c0,0 -1,-1 -1,-1 0,-5 0,-9 0,-14 0,-2 3,-3 5,-3z"/>
        <path fill="#b9b9b9" d="M189 60c-1,-2 -2,-3 -4,-3l-4 0c-2,0 -3,1 -3,3l0 10c0,2 1,4 3,4l4 0c2,0 3,-2 4,-4l0 7c0,0 0,1 1,1l0 0c0,10 -10,18 -22,27 -9,7 -20,15 -29,26 -4,6 -11,10 -19,15 -13,8 -26,17 -25,29l1 2 2 -1 0 -1c-1,-11 11,-19 23,-27 8,-5 15,-9 20,-15 9,-11 19,-19 29,-26 12,-10 23,-17 23,-29l0 0c0,0 1,-1 1,-1 0,-5 0,-9 0,-14 0,-2 -3,-3 -5,-3z"/>
      </g>
    </svg>
   </div>
  <div @click="OptionsHair = true; mainOpt = false">
    <svg viewBox="0 0 180 180">
      <g id="h_shorthairwaved">
        <path fill="#000000" fill-opacity="0.2" d="M158 116l1 -8c4,-37 -31,-69 -69,-69l0 0c-38,0 -76,32 -69,69l2 8c2,-11 2,-16 9,-33 3,-6 7,-10 12,-15 3,-3 5,-5 7,-9 24,18 52,15 78,2 1,3 2,5 5,7 1,2 4,3 6,5 2,2 4,4 5,6 9,18 9,22 13,37z"/>
        <path class="tinted" fill="#bb7748" d="M161 116c5,-9 8,-5 8,-31 0,-31 -9,-31 -15,-44 -3,-4 15,-16 0,-31 -13,-12 -22,3 -35,3 -7,-1 -15,-3 -23,-5 -8,-2 -31,-3 -43,4 -11,8 -20,17 -21,28 -14,10 -20,27 -20,45 0,11 3,22 7,31 1,0 3,0 4,0 0,-47 19,-43 27,-62 22,19 50,18 81,2 4,18 22,5 27,60l3 0z"/>
      </g>
    </svg>
  </div>
  <div @click="OptionsEyes = true; mainOpt = false">
    <svg viewBox="0 0 180 180">
      <g id="e_surprised">
        <circle fill="#e5e5e5" cx="50" cy="100" r="22"/>
        <circle fill="#4D4D4D" stroke="#5F4A37" stroke-width="0.9" cx="50" cy="100" r="10"/>
        <circle fill="#e5e5e5" cx="125" cy="100" r="22"/>
        <circle fill="#4D4D4D" cx="125" cy="100" r="10"/>
      </g>
    </svg>
  </div>
  <div @click="OptionsMouths = true; mainOpt = false">
    <svg viewBox="0 0 80 80">
      <g id="m_smile">
        <path fill="#000000" d="M40 60l0 0c13,0 24,-10 24,-23l0 -1 -48 0 0 1c0,13 11,23 24,23z"/>
        <path fill="#FF4F6D" d="M40 60l0 0c6,0 11,-2 16,-5 -2,-3 -5,-5 -9,-5 -3,0 -5,1 -7,2 -2,-1 -4,-2 -7,-2 -4,0 -7,2 -9,5 5,3 10,5 16,5z"/>
        <path fill="#FEFEFE" d="M59 36l-38 0 0 2c0,3 2,5 4,5l30 0c2,0 4,-2 4,-5l0 -2z"/>
      </g>
    </svg>
  </div>
  <div @click="OptionGlasses = true; mainOpt = false">
    <svg viewBox="0 0 800 800">
      <g id="g_rambo">
        <path d="M353.7,85.738c6.5-2,13.5-1.3,19.5,1.9c6,3.2,10.4,8.6,12.4,15.1v0.1c0,0,0,0,0,0.1l43,136.4c-13-5.9-27.5-9.2-42.7-9.2
				c-52,0-95.1,38.4-102.5,88.4H206c-8.2-49-50.9-86.5-102.3-86.5c-15.3,0-29.8,3.3-42.8,9.3l43.5-138.3c0,0,0,0,0-0.1v-0.1
				c4.1-13.5,18.4-21.1,31.9-17c9.1,2.7,18.6-2.4,21.4-11.4c2.8-9.1-2.4-18.6-11.4-21.4c-31.5-9.6-64.9,8.2-74.6,39.6c0,0,0,0,0,0.1
				v0.1l0,0l0,0l-63.8,202.6c-0.2,0.6-0.3,1.2-0.5,1.8c-4.8,11.9-7.4,24.9-7.4,38.4c0,57.2,46.5,103.7,103.7,103.7
				c51.3,0,94.1-37.5,102.3-86.5h78c8.9,48.1,51.2,84.7,101.9,84.7c57.2,0,103.7-46.5,103.7-103.7c0-13.7-2.7-26.7-7.5-38.7
				l-63.8-202.5v-0.1c-4.7-15.2-15-27.7-29-35.2c-14.1-7.5-30.3-9.1-45.6-4.5c-9.1,2.8-14.2,12.3-11.4,21.4
				C335,83.438,344.6,88.538,353.7,85.738z M103.7,405.038c-38.3,0-69.4-31.1-69.4-69.4s31.1-69.4,69.4-69.4s69.4,31.1,69.4,69.4
				S142,405.038,103.7,405.038z M385.9,403.238c-38.3,0-69.4-31.1-69.4-69.4s31.1-69.4,69.4-69.4s69.4,31.1,69.4,69.4
				S424.1,403.238,385.9,403.238z"/>
     </g>
    </svg>
  </div>
  <div @click="OptionsClothes = true; mainOpt = false">
    <svg viewBox="0 0 280 280">
      <g id="cc_blazer">
        <path class="tinted" fill="#545454" d="M264 280l0 -13c0,-45 -34,-83 -79,-87l-1 -1c-2,0 -4,0 -6,0 1,0 1,1 1,1l-1 0 1 0c0,2 0,3 0,5l-3 2c-24,23 -48,23 -72,0l-3 -2c0,-2 0,-4 1,-6 -2,0 -4,0 -6,0l-1 1c-45,4 -79,42 -79,87l0 13 74 0 19 0 62 0 19 0 74 0z"/>
        <path fill="#000000" fill-opacity="0.5" d="M90 280l-20 -45c3,-4 5,-7 7,-10 -2,-3 -4,-7 -7,-10l26 -36c2,0 4,0 6,0 -5,35 0,74 7,101l-19 0z"/>
        <path fill="#000000" fill-opacity="0.5" d="M190 280l20 -45c-3,-4 -5,-7 -7,-10 2,-3 4,-7 7,-10l-26 -36c-2,0 -4,0 -6,0 5,35 0,74 -7,101l19 0z"/>
        <path fill="#ffffff" d="M204 230c10,-10 12,-13 23,-2 -8,1 -15,2 -23,2z"/>
        <path fill="#000000" fill-opacity="0.7" d="M180 200c-27,24 -54,23 -80,-1 0,-1 1,-3 1,-5l3 2c24,23 48,23 72,0l3 -2c0,2 1,4 1,6z"/>
        <path fill="#000000" fill-opacity="0.3" d="M109 280l62 0c6,-24 11,-57 9,-89 -2,1 -4,3 -6,5 -4,2 -7,5 -11,7 -21,11 -42,6 -63,-12 -2,32 3,65 9,89z"/>
      </g>
    </svg>
  </div>
  <div @click="OptionTattoos = true; mainOpt = false">
    <svg viewBox="0 0 180 180">
      <g id="t_throat">
        <path fill="#000000" fill-opacity="0.7" fill-rule="nonzero" d="M20 100c0,-1 1,-1 2,-1 0,0 1,1 1,2 -1,1 -3,2 -4,1 0,1 0,1 0,1 4,3 6,6 7,7 0,0 1,0 2,-1 1,0 3,0 4,0l0 0c3,0 6,1 7,5 0,0 0,1 0,1l0 0c0,2 -1,3 -2,4 -1,0 -1,0 -2,0 -1,1 -1,1 -2,1 0,0 -1,0 -1,0 1,1 3,2 6,3 2,2 7,3 13,5 5,1 9,4 12,7 3,4 5,7 6,9 -1,-4 -2,-8 -3,-11 -1,0 -1,0 -1,0 0,-1 0,-1 0,-2 -2,-4 -4,-7 -6,-10 -3,-4 -5,-6 -6,-8 -1,-1 -1,-1 -1,-1 0,1 1,1 1,2 0,1 0,1 0,2 0,1 -1,2 -1,3 -1,1 -2,1 -3,1 0,0 0,0 0,0 -1,-1 -3,-2 -4,-3 -1,-1 -2,-3 -2,-5 0,0 0,-1 0,-1 0,-3 2,-5 4,-6 2,-2 4,-2 5,-2 -5,-11 11,-11 12,2 3,-20 23,-31 23,-10 0,-21 20,-10 23,10 1,-13 17,-13 12,-2 1,0 3,0 5,2 2,1 4,3 4,6 0,0 0,1 0,1 0,2 -1,4 -2,5 -1,1 -3,2 -4,3 0,0 0,0 0,0 -1,0 -2,0 -3,-1 0,-1 -1,-2 -1,-3 0,-1 0,-1 0,-2 0,-1 1,-1 1,-2 0,0 0,0 -1,1 -1,2 -3,4 -6,8 -2,3 -4,6 -6,10 0,1 0,1 0,2l-1 0c-1,3 -2,7 -3,11 1,-2 3,-5 6,-9 3,-3 7,-6 12,-7 6,-2 11,-3 13,-5 3,-1 5,-2 6,-3 0,0 -1,0 -1,0 -1,0 -1,0 -2,-1 -1,0 -1,0 -2,0 -1,-1 -2,-2 -2,-4l0 0c0,0 0,-1 0,-1 1,-4 4,-5 7,-5l0 0c1,0 3,0 4,0 1,1 2,1 2,1 1,-1 3,-4 7,-7 0,0 0,0 0,-1 -1,1 -3,0 -4,-1 0,-1 1,-2 1,-2 1,0 2,0 2,1 2,-2 3,-5 1,-8 -1,-4 -4,-4 -4,-4 0,11 -17,13 -24,5 -2,-2 -3,-5 -2,-7 3,-2 4,2 5,4 1,-18 -10,-24 -10,-24 3,7 4,18 -5,21 -5,2 -12,-5 -4,-4 -4,-4 -12,-3 -19,-2 1,-1 1,-1 2,-2 0,0 0,0 0,0 0,0 0,0 1,-1 2,-1 6,-1 9,-1 0,0 1,0 1,1 1,0 1,0 1,0 0,0 0,0 -1,-1 0,0 0,0 -1,0 -3,-1 -5,-3 -8,-5 2,-1 4,-2 7,-2 0,-1 1,-1 2,-1 1,0 3,1 4,1 3,2 4,4 6,5 3,-6 2,-16 -2,-21 1,4 -2,8 -6,9 -2,1 -4,2 -7,1 -1,0 -2,-1 -3,-2 0,-1 0,-2 0,-3 1,-3 1,-7 0,-11 -1,1 -2,1 -3,1 0,0 0,1 0,1 0,2 -1,4 -1,5 -1,2 -3,4 -4,6 -1,1 -1,2 -2,3 -1,-1 -2,-2 -2,-3 -2,-1 -3,-3 -4,-6 0,-1 -1,-3 -1,-4 0,-1 -1,-2 -1,-2 -1,0 -2,0 -3,-1 0,4 0,8 0,11 0,1 1,2 1,3 -1,1 -2,2 -3,2 -3,1 -5,0 -8,-1 -3,-1 -6,-5 -5,-9 -4,5 -6,15 -2,21 1,-1 3,-3 6,-5 1,0 2,-1 4,-1 1,0 1,0 2,1 3,0 5,1 7,2 -3,2 -6,4 -9,5 0,0 0,0 -1,0 0,1 0,1 -1,1 1,0 1,0 2,0 0,-1 0,-1 1,-1 3,0 6,0 9,1 0,1 1,1 1,1 0,0 0,0 0,0 1,1 1,1 2,2 -8,-1 -15,-2 -19,2 8,-1 1,6 -4,4 -9,-3 -8,-14 -5,-21 0,0 -11,6 -10,24 1,-2 2,-6 5,-4 1,2 0,5 -2,7 -7,8 -24,6 -24,-5 0,0 -3,0 -4,4 -2,3 -1,6 1,8z"/>
      </g>
    </svg>
  </div>
  </div>

  <div id="optionsFacialHair" v-if="facialHair === true">
    <OptionsFacialHair />
  </div>

  <div id="optionsGlasses" v-if="OptionGlasses === true">
    <OptionsGlasses />
  </div>

  <div id="optionsMouths" v-if="OptionsMouths === true">
    <OptionsMouths />
  </div>

  <div id="optionsClothes" v-if="OptionsClothes === true">
    <OptionsClothes />
  </div>

  <div id="optionsEyes" v-if="OptionsEyes === true">
    <OptionsEyes />
  </div>

  <div id="OptionsEyebrows" v-if="OptionsEyebrows === true">
    <OptionsEyebrows />
  </div>

  <div id="OptionsHair" v-if="OptionsHair === true">
    <OptionsHair />
  </div>

  <div id="OptionTattoos" v-if="OptionTattoos === true">
    <OptionTattoos />
  </div>

  <div id="OptionsAccesories" v-if="OptionsAccesories === true">
    <OptionsAccesories />
  </div>

  <div id="backArrow" v-if="mainOpt === false" @click="resetMenu()">
    <img :src="require('../assets/img/back.png')">
  </div>

</div>

</template>



<script>
import  OptionsFacialHair  from './options/facialhair'
import  OptionsGlasses     from './options/glasses'
import  OptionsMouths      from './options/mouths'
import  OptionsClothes     from './options/clothes'
import  OptionsEyes        from './options/eyes'
import  OptionsEyebrows    from './options/eyebrows'
import  OptionsHair        from './options/hair'
import  OptionTattoos      from './options/tattoos'
import  OptionsAccesories  from './options/accesories'


function initialState() {
  return {
    mainOpt: true,
    facialHair: false,
    OptionGlasses: false,
    OptionsMouths: false,
    OptionsClothes: false,
    OptionsEyes: false,
    OptionsEyebrows: false,
    OptionsHair: false,
    OptionTattoos: false,
    OptionsAccesories: false
  }
}

export default {
  name: "Options",
  components: {
    OptionsFacialHair,
    OptionsGlasses,
    OptionsMouths,
    OptionsClothes,
    OptionsEyes,
    OptionsEyebrows,
    OptionsHair,
    OptionTattoos,
    OptionsAccesories
  },
  data() {
    return initialState();
  },
  methods: {
    resetMenu() {
      Object.assign(this.$data, initialState());
    }
  },
  created() {
    this.$root.$refs.Options = this;
  }
}
</script>
