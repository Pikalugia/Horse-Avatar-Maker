<template>

<div id="OptionSkinColor">

</div>

</template>

<script>
export default {
  name: "OptionSkinColor",
  methods: {
    deleteClass() {
      let c = document.getElementById('skinColor').children, i;
      for (i = 0; i < c.length; i++) {
        c[i].classList.remove('show');
      }
    },
    showWhiteSkin() {
      this.deleteClass();
      document.querySelector('#skin_white').classList.add('show');
    },
    showBlackSkin() {
      this.deleteClass();
      document.querySelector('#skin_black').classList.add('show');
    }
  }
}
</script>
