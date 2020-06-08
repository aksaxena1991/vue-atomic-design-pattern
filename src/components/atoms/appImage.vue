<template>
  
    <img v-bind:src="src" v-bind:width="width" v-bind:height="height">
  
    
  
</template>

<script>
export default {
  name: 'AppImage',
  data(){
    return{
      height:null,
      width:null,
      src:null
      
    }
  },
  props:{
    url:null,
      h:null,
      w:null
  },
  mounted() {
    this.src = this.url;
    this.height = this.h;
    this.width = this.w;
    
  }
}
</script>

<style scoped>

</style>
