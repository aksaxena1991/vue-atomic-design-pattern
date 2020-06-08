<template>
  <div class="appCancelbar">
    <AppTitle v-html="heading"></AppTitle>
    <ul>
      <li><AppCrossButton type="button" label="Element Name"/> </li>
    </ul>
     
     
    
  </div>
</template>

<script>
import AppCrossButton from '../atoms/AppCrossButton';
import AppTitle from '../atoms/AppTitle';
export default {
  name: 'AppSearchItem',
  data: ()=> 
  ({
    heading:'Selected Filters'
    
  }),
  components: {AppCrossButton,
  
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
