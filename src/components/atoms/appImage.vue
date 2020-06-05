<template>
  <div>
    <img v-bind:src={source} v-bind:width={width} v-bind:height={height}>
  </div>
    
  
</template>

<script>
export default {
  name: 'appImage',
  data:()=>({
  }),
  props: {
    source: String,
    height:String,
    width:String
  },
  mounted() {
    console.log(this);
  }
}
</script>

<style scoped>

</style>
