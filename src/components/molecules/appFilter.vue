<template>
  <div class="appFilter">
    <AppTitle v-html="heading"></AppTitle>
    <ul>
      <li v-for="(checkbox,index) in checkboxes" v-bind:key="index">
        <AppCheckbox :value='checkbox.value' :label="checkbox.label" :model="heading"/>
      </li>
      
    </ul>
  </div>
</template>

<script>
import AppCheckbox from '../atoms/appCheckbox';
import AppTitle from '../atoms/appTitle';
export default {
  name: 'AppFilter',
  data: ()=> 
  ({
    heading:null,
    checkboxes: []
  }),
  components: {AppCheckbox,
  AppTitle
  },
  props: {
    data:null
  },
  mounted() {
    this.heading = this.data.obj.heading;
    this.checkboxes = this.data.obj.checkbox
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
