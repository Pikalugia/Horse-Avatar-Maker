<template>
  
<div class="mn">

  <div @click="showHarry()">
    <svg viewBox="0 0 100 100">
     <g id="t_harry">
      <polygon fill="#000000" fill-opacity="0.7" points="47,14 63,50 47,47 49,69 37,40 55,43 "/> <!--  points="127,34 143,70 127,67 129,89 117,60 135,63 "/>    -->
     </g>
    </svg>
  </div>


</div>

</template>

<script>
export default {
  name: "OptionsTattoos",
  methods: {
    deleteClass() {
      let c = document.getElementById('tattoos').children, i;
      for (i = 0; i < c.length; i++) {
        c[i].classList.remove('show');
      }
    },
    showHarry() {
      if(document.querySelector('#t_harry').classList.contains('show')) {
        this.deleteClass();
      } else {
        this.deleteClass();
        document.querySelector('#t_harry').classList.add('show');
      }
    },

    showAirBender() {
      if(document.querySelector('#t_airbender').classList.contains('show')) {
        this.deleteClass();
      } else {
        this.deleteClass();
        document.querySelector('#t_airbender').classList.add('show');
      }
    },

    showKrilin() {
      if(document.querySelector('#t_krilin').classList.contains('show')) {
        this.deleteClass();
      } else {
        this.deleteClass();
        document.querySelector('#t_krilin').classList.add('show');
      }
    },
    showFront() {
      if(document.querySelector('#t_front').classList.contains('show')) {
        this.deleteClass();
      } else {
        this.deleteClass();
        document.querySelector('#t_front').classList.add('show');
      }
    },
    showTribal() {
      if(document.querySelector('#t_tribal').classList.contains('show')) {
        this.deleteClass();
      } else {
        this.deleteClass();
        document.querySelector('#t_tribal').classList.add('show');
      }
    },
    showTribal2() {
      if(document.querySelector('#t_tribal2').classList.contains('show')) {
        this.deleteClass();
      } else {
        this.deleteClass();
        document.querySelector('#t_tribal2').classList.add('show');
      }
    },
    showThroat(){
      if(document.querySelector('#t_throat').classList.contains('show')) {
        this.deleteClass();
      } else {
        this.deleteClass();
        document.querySelector('#t_throat').classList.add('show');
      }
    }
  }
}


</script>
