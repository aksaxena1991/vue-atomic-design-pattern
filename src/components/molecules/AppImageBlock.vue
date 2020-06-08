<template>
  <div class="appImageblock">
    
      <AppImage :h="height" :w="width" :url="imgUrl"/>
    
  </div>
</template>

<script>
import AppImage from "../atoms/AppImage";
export default {
  name: 'AppImageBlock',
  data: ()=> 
  ({
    imgUrl:"https://firebasestorage.googleapis.com/v0/b/tracker-covid-19.appspot.com/o/6cy5ke99i.jpg?alt=media&token=f036a550-e382-4581-8fae-71bdedf41f1e",
    height:'400px',
    width:'400px'
  }),
  components: {
    AppImage
  },
  props: {
    
  },
  mounted() {
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
