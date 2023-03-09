<template>

<div id="options">
 <div id="main" class="mn" v-if="mainOpt === true">
  <div @click="OptionsAccesories = true; mainOpt = false">
    <svg viewBox="0 0 100 100">
      <g id="a_optionsaccessories">
        <path d="M 56.797 12.750 C 55.380 14.262, 53.250 17.434, 52.065 19.799 C 49.659 24.597, 50.163 24.328, 40.348 26.038 C 33.652 27.204, 32.982 27.151, 29.848 25.208 C 28.006 24.066, 24.925 21.498, 23 19.500 C 19.098 15.451, 13.192 11.475, 12.341 12.325 C 11.587 13.080, 14.920 21.863, 17.245 25.248 C 18.283 26.759, 21.128 29.368, 23.566 31.046 C 26.005 32.723, 27.998 34.637, 27.996 35.298 C 27.994 35.959, 26.658 39.180, 25.027 42.456 C 20.727 51.091, 20.367 55.343, 23.024 66.098 C 25.556 76.345, 29.343 82.387, 35.027 85.248 C 39.269 87.384, 48.720 87.562, 53.427 85.595 C 56.579 84.278, 57.016 84.350, 60.374 86.740 C 64.595 89.743, 72.108 90.780, 77.280 89.073 C 81.314 87.741, 83.487 83.790, 82.453 79.669 C 81.899 77.461, 82.208 76.871, 84.345 76.059 C 87.735 74.770, 89.434 68.554, 88.545 60.695 C 87.630 52.612, 87.415 52.261, 81.633 49.468 C 75.262 46.390, 70 41.670, 70 39.034 C 70 37.938, 69.299 35.290, 68.443 33.150 C 67.233 30.124, 65.983 28.904, 62.823 27.663 C 59.574 26.386, 58.905 25.710, 59.482 24.283 C 60.691 21.299, 61.356 10, 60.324 10 C 59.802 10, 58.214 11.238, 56.797 12.750" stroke="none" fill="#000000" fill-rule="evenodd"/>
	</g>
    </svg>
   </div>
  <div @click="OptionsHair = true; mainOpt = false">
    <svg viewBox="0 0 512 512">
      <g id="h_optionshair">
        <path class="st0" d="M511.883,298.395c-2.781-27.281-54.391-46.141-129.406-51.844c-7.172-42.047-15.469-90.563-17.891-103.75 c-5.563-30.203-45.344-47.094-74.891-25.313c-15.5,11.422-29.359,12.234-36.703,12.234s-15.5,1.625-36.703-12.234 c-30.719-20.094-69.328-4.891-74.875,25.313c-2.969,16.109-14.688,84.844-22.391,130.203 C45.211,293.817-2.711,323.114,0.117,350.723c4.25,41.625,122.266,63.671,263.578,49.218 C405.039,385.488,516.148,340.036,511.883,298.395z M132.289,308.348l8.156-42.406c0,0,145.188,22.828,226.75-19.578l8.156,35.891 C375.352,282.254,287.258,337.708,132.289,308.348z"></path>
      </g>
    </svg>
  </div>
  <div @click="OptionsEyes = true; mainOpt = false">
    <svg viewBox="0 0 12 12">
      <g id="e_optionseyes">
        <path d="M6,2C4,2,2,3,0,6c2,3,4,4,6,4s4-1,6-4C10,3,8,2,6,2z M6,8.5C4.621582,8.5,3.5,7.3789063,3.5,6 S4.621582,3.5,6,3.5S8.5,4.6210938,8.5,6S7.378418,8.5,6,8.5z" fill="#1D1D1B"></path>
      </g>
    </svg>
  </div>
  <div @click="OptionGlasses = true; mainOpt = false">
    <svg viewBox="0 0 100 100">
      <g id="g_optionsglasses">
        <path d="M 73 33.071 C 62.535 34.252, 59.075 35.444, 54.681 39.379 C 51.720 42.031, 49.360 43.079, 44.181 44.041 C 40.506 44.724, 36.375 45.779, 35 46.387 C 33.539 47.032, 26.263 47.493, 17.500 47.496 L 2.500 47.500 2.192 52.328 C 1.889 57.077, 3.329 60.533, 5.144 59.411 C 5.649 59.099, 5.759 57.232, 5.389 55.261 C 4.783 52.030, 4.903 51.749, 6.608 52.410 C 7.649 52.813, 12.231 54.032, 16.792 55.119 C 28.111 57.816, 27.516 57.408, 29.988 64.186 C 34.348 76.146, 40.818 79.910, 51.218 76.539 C 59.476 73.862, 63.809 68.814, 66.341 58.919 C 67.864 52.971, 69.915 51.851, 71.109 56.315 C 72.263 60.630, 76.658 65.766, 79.784 66.452 C 89.797 68.652, 98.727 54.820, 97.830 38.500 L 97.500 32.500 89 32.362 C 84.325 32.286, 77.125 32.605, 73 33.071 M 59.796 40.050 L 56.619 43.227 60.560 44.695 C 67.870 47.418, 68.263 47.367, 72.355 43.162 C 76.668 38.730, 76.673 38.735, 67.736 37.521 C 63.319 36.920, 62.742 37.104, 59.796 40.050" stroke="none" fill="#000000" fill-rule="evenodd"/>
     </g>
    </svg>
  </div>
  <div @click="OptionsClothes = true; mainOpt = false">
    <svg viewBox="0 0 100 100">
      <g id="cc_optionsclothes">
        <path d="M 29.766 17.223 C 25.794 18.052, 24.064 19.245, 19.016 24.642 C 15.707 28.179, 13 31.963, 13 33.051 C 13 35.171, 18.285 38.990, 21.227 38.996 C 22.177 38.998, 23.691 37.875, 24.592 36.500 C 25.493 35.125, 26.675 34, 27.219 34 C 27.762 34, 26.820 35.580, 25.124 37.512 C 22.433 40.576, 13.859 56.980, 10.954 64.620 C 9.482 68.494, 10.513 70.463, 16.129 74.497 C 24.508 80.517, 51.193 86.375, 59.740 84.071 C 64.617 82.757, 64.354 83.480, 65.944 67 C 67.575 50.094, 68.488 43.179, 69.180 42.487 C 69.519 42.148, 70.539 44.108, 71.448 46.843 C 72.356 49.578, 74.182 52.983, 75.505 54.411 L 77.910 57.006 83.205 54.932 C 86.117 53.791, 88.887 52.480, 89.360 52.018 C 90.359 51.045, 87.751 42.534, 84.451 36 C 80.947 29.061, 76.400 25.371, 67.227 22.024 C 51.958 16.451, 40.508 14.984, 29.766 17.223" stroke="none" fill="#000000" fill-rule="evenodd"/>
	</g>
    </svg>
  </div>
  <div @click="facialHair = true; mainOpt = false">
    <svg viewBox="0 0 100 100">
      <g id="cc_optionsfacialhair">
        <path d="M 22.512 40.520 C 20.869 41.404, 18.109 43.674, 16.378 45.564 C 14.647 47.454, 12.559 49, 11.738 49 C 10.917 49, 9.788 48.438, 9.230 47.750 C 8.672 47.063, 8.048 45.600, 7.844 44.500 C 7.640 43.400, 6.853 42.500, 6.095 42.500 C 5.338 42.500, 4.268 43.214, 3.717 44.087 C 3.167 44.959, 3.015 47.269, 3.381 49.219 C 3.747 51.169, 5.345 54.557, 6.933 56.749 C 8.587 59.032, 11.820 61.703, 14.501 63 C 17.075 64.247, 21.066 65.479, 23.371 65.738 C 25.956 66.030, 29.027 65.598, 31.391 64.610 C 35.134 63.046, 35.292 63.068, 38.245 65.552 C 39.907 66.951, 42.941 68.949, 44.986 69.993 C 47.031 71.036, 51.773 72.424, 55.523 73.077 C 59.417 73.756, 65.459 74.001, 69.613 73.650 C 73.613 73.312, 79.188 72.160, 82.002 71.091 C 84.816 70.022, 88.720 67.925, 90.678 66.432 C 92.636 64.939, 95.136 61.686, 96.234 59.205 C 97.701 55.888, 98.070 53.530, 97.628 50.306 C 97.298 47.893, 96.555 45.037, 95.978 43.960 C 95.402 42.882, 94.039 42, 92.949 42 C 91.188 42, 90.995 42.607, 91.200 47.507 C 91.387 51.986, 91.032 53.412, 89.298 55.146 C 87.898 56.547, 85.464 57.441, 82.200 57.755 C 79.468 58.017, 75.521 57.667, 73.428 56.976 C 71.309 56.277, 66.672 52.949, 62.961 49.463 C 59.296 46.021, 54.903 42.484, 53.199 41.603 C 51.494 40.721, 47.927 40, 45.272 40 C 42.466 40, 39.489 40.670, 38.161 41.600 C 36.064 43.069, 35.729 43.065, 34.063 41.557 C 33.065 40.654, 30.730 39.689, 28.874 39.414 C 26.803 39.106, 24.347 39.533, 22.512 40.520" stroke="none" fill="#000000" fill-rule="evenodd"/>
      </g>
    </svg>
  </div>
  
  
  </div>

  <div id="facialHair" v-if="facialHair === true">
    <facialHair />
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
import  facialHair  from './options/facialhair'
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
    facialHair,
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
