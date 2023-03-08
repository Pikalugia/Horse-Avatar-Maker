<template>

<div id="options">
 <div id="main" class="mn" v-if="mainOpt === true">
  <div @click="OptionsAccesories = true; mainOpt = false">
    <svg viewBox="0 0 100 100">
      <g id="a_earphones">
        <path d="M 56.797 12.750 C 55.380 14.262, 53.250 17.434, 52.065 19.799 C 49.659 24.597, 50.163 24.328, 40.348 26.038 C 33.652 27.204, 32.982 27.151, 29.848 25.208 C 28.006 24.066, 24.925 21.498, 23 19.500 C 19.098 15.451, 13.192 11.475, 12.341 12.325 C 11.587 13.080, 14.920 21.863, 17.245 25.248 C 18.283 26.759, 21.128 29.368, 23.566 31.046 C 26.005 32.723, 27.998 34.637, 27.996 35.298 C 27.994 35.959, 26.658 39.180, 25.027 42.456 C 20.727 51.091, 20.367 55.343, 23.024 66.098 C 25.556 76.345, 29.343 82.387, 35.027 85.248 C 39.269 87.384, 48.720 87.562, 53.427 85.595 C 56.579 84.278, 57.016 84.350, 60.374 86.740 C 64.595 89.743, 72.108 90.780, 77.280 89.073 C 81.314 87.741, 83.487 83.790, 82.453 79.669 C 81.899 77.461, 82.208 76.871, 84.345 76.059 C 87.735 74.770, 89.434 68.554, 88.545 60.695 C 87.630 52.612, 87.415 52.261, 81.633 49.468 C 75.262 46.390, 70 41.670, 70 39.034 C 70 37.938, 69.299 35.290, 68.443 33.150 C 67.233 30.124, 65.983 28.904, 62.823 27.663 C 59.574 26.386, 58.905 25.710, 59.482 24.283 C 60.691 21.299, 61.356 10, 60.324 10 C 59.802 10, 58.214 11.238, 56.797 12.750" stroke="none" fill="#000000" fill-rule="evenodd"/>
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
