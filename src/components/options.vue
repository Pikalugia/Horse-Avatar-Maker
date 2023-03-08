<template>

<div id="options">
 <div id="main" class="mn" v-if="mainOpt === true">
  <div @click="OptionsAccesories = true; mainOpt = false">
    <svg viewBox="0 0 512 512">
      <g id="a_earphones">
        <path class="st0" d="M508.692,167.211c-14.625,0.984-64.391,5.859-128.781,5.859c-90.734,0-96.594,32.188-123.922,32.188 c-31.203,0-29.25-32.188-123.906-32.188c-64.391,0-114.156-4.875-128.781-5.859c-10.531-0.703,3.906,103.406,46.828,142.438 c32.5,29.547,111.234,54.656,172.703,13.656c23.422-18.516,33.156-18.516,33.156-18.516s9.781,0,33.188,18.516 c61.453,41,140.203,15.891,172.688-13.656C504.786,270.617,519.239,166.508,508.692,167.211z M202.442,255.305 c-45.656,50.922-120.297,15.797-121.172-35.141C165.552,207.008,205.755,251.602,202.442,255.305z M309.552,255.305 c-3.313-3.703,36.875-48.297,121.172-35.141C429.849,271.102,355.224,306.227,309.552,255.305z"></path>
      </g>
    </svg>
   </div>
  <div @click="OptionsHair = true; mainOpt = false">
    <svg viewBox="0 0 512 512">
      <g id="h_shorthairwaved">
        <path class="st0" d="M511.883,298.395c-2.781-27.281-54.391-46.141-129.406-51.844c-7.172-42.047-15.469-90.563-17.891-103.75 c-5.563-30.203-45.344-47.094-74.891-25.313c-15.5,11.422-29.359,12.234-36.703,12.234s-15.5,1.625-36.703-12.234 c-30.719-20.094-69.328-4.891-74.875,25.313c-2.969,16.109-14.688,84.844-22.391,130.203 C45.211,293.817-2.711,323.114,0.117,350.723c4.25,41.625,122.266,63.671,263.578,49.218 C405.039,385.488,516.148,340.036,511.883,298.395z M132.289,308.348l8.156-42.406c0,0,145.188,22.828,226.75-19.578l8.156,35.891 C375.352,282.254,287.258,337.708,132.289,308.348z"></path>
      </g>
    </svg>
  </div>
  <div @click="OptionsEyes = true; mainOpt = false">
    <svg viewBox="0 0 100 100">
      <g id="e_surprised">
        <path d="M6,2C4,2,2,3,0,6c2,3,4,4,6,4s4-1,6-4C10,3,8,2,6,2z M6,8.5C4.621582,8.5,3.5,7.3789063,3.5,6 S4.621582,3.5,6,3.5S8.5,4.6210938,8.5,6S7.378418,8.5,6,8.5z" fill="#1D1D1B"></path>
      </g>
    </svg>
  </div>
  <div @click="OptionsMouths = true; mainOpt = false">
    <svg viewBox="0 0 100 100">
      <g id="m_smile">
        <path d="M27.936,5.153c-0.644-2.089-2.629-3.698-4.123-4.654c-1.021-0.651-2.324-0.666-3.357-0.039l-2.667,1.616 c-1.207,0.731-2.718,0.731-3.924,0L11.198,0.46C10.163-0.167,8.86-0.152,7.841,0.499C6.345,1.455,4.359,3.064,3.716,5.153 C2.64,8.647,1.028,12.947,5.059,17.786c0,0-2.149,9.139,2.956,13.438c0,0,3.73,1.68,3.226-1.612 c-0.327-2.139-0.303-10.059,4.585-10.445c4.889,0.387,4.913,8.308,4.584,10.445c-0.503,3.292,3.226,1.612,3.226,1.612 c5.106-4.3,2.957-13.438,2.957-13.438C30.625,12.948,29.012,8.647,27.936,5.153z"></path>
      </g>
    </svg>
  </div>
  <div @click="OptionGlasses = true; mainOpt = false">
    <svg viewBox="0 0 512 512">
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
    <svg viewBox="0 0 512 512">
      <g id="cc_blazer">
        <path d="M485.29,89.9,356,44.64a4,4,0,0,0-5.27,3.16,96,96,0,0,1-189.38,0A4,4,0,0,0,156,44.64L26.71,89.9A16,16,0,0,0,16.28,108l16.63,88A16,16,0,0,0,46.83,208.9l48.88,5.52a8,8,0,0,1,7.1,8.19l-7.33,240.9a16,16,0,0,0,9.1,14.94A17.49,17.49,0,0,0,112,480H400a17.49,17.49,0,0,0,7.42-1.55,16,16,0,0,0,9.1-14.94l-7.33-240.9a8,8,0,0,1,7.1-8.19l48.88-5.52A16,16,0,0,0,479.09,196l16.63-88A16,16,0,0,0,485.29,89.9Z"></path>
      </g>
    </svg>
  </div>
  <div @click="OptionTattoos = true; mainOpt = false">
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
