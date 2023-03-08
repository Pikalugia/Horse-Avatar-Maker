<template>
</template>

<script>
export default {
  name: "SkinColor",
  data() {
    return {
      list: ['#skin_white','#skin_black']
    }
  },

  methods: {
    picker(option = false) {
      this.hide_all();
      option
        ? document.querySelector(option).classList.add('show')
        : document.querySelector(this.random_option()).classList.add('show');
    },
    random_option() {
      var chosenSkinColor = Math.floor(Math.random() * this.list.length);
      return this.list[chosenSkinColor];
    },
    hide_all() {
      for (let i = 0; i < this.list.length; i++) {
        document.querySelector(this.list[i]).classList.remove('show');
      }
    }
  },

  created() {
    this.$root.$refs.SkinColor = this;
  }
}
</script>
