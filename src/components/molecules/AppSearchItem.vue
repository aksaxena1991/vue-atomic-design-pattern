<template>
  <div class="appSearchitem">
    <AppTitle v-html="heading"></AppTitle>
    <legend>
     <AppInput placeholder="Search Item" type="input"/>
     <AppButton type="button" label="Search"/> 
    </legend>
  </div>
</template>

<script>
import AppInput from '../atoms/AppInput';
import AppButton from '../atoms/AppButton';
import AppTitle from '../atoms/AppTitle';
export default {
  name: 'AppSearchItem',
  data: ()=> 
  ({
    heading:'Search By Name'
    
  }),
  components: {AppButton,
  AppInput,
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
