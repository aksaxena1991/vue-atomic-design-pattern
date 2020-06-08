<template>
  <div class="appImagerHeader">
    <AppTitle/>
    <AppParagraph/>
     
     
    
  </div>
</template>

<script>
import AppParagraph from '../atoms/AppParagraph';
import AppTitle from "../atoms/AppTitle";
export default {
  name: 'AppImageHeader',
  data: ()=> 
  ({
    
    
  }),
  components: {
    AppParagraph,
    AppTitle
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
