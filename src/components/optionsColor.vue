<template>
</template>



<script>
import OptionSkinColor from './options/SkinColor'

function initialState() {
  return {
    OptionShowPicker: false
  }
}

export default {
  name: "OptionsColor",
  components: {
    OptionSkinColor
  },
  data() {
    return initialState();
  },
  methods: {
    showOptions() {
      if (this.OptionShowPicker == true) {
        this.OptionShowPicker = false;
      } else {
        this.OptionShowPicker = true;
      }
    }
  },
  created() {
    this.$root.$refs.OptionsColor = this;
  }
}
</script>
