<template>
  <div id="app">
    <input type="button" value="切换" v-on:click="aaabbb"/>
    <component :is="currentTabComponent"></component>
  </div>
</template>

<script>
import aaa from './components/aaa.vue'

  export default {
    el:"#app",
    data() {
      return {
        currentTabComponent:aaa,
        nnn:123
        lia:1
      }
    },
    methods: {
      aaabbb:function(){
        console.log(this,1)
      }
    },
  }
</script>




