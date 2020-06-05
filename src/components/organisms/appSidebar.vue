<template>
  <div>
    <AppTitle title="Filters"/>
    <div v-for="(obj,index) in data.filterObject" v-bind:key="index">
      <AppFilter :data="{obj}"/>
    </div>
    
    <!-- <appFilter/>
    <appFilter/> -->
  </div>
</template>

<script>
import AppFilter from '../molecules/appFilter';
import AppTitle from '../atoms/appTitle';
export default {
  name: 'AppSidebar',
  data () {
    return {}
  },
  props:{
    data:null
  },
  components: {
    AppFilter,
    AppTitle
  },
  mounted() {
    // console.log(this,'anubhav');
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
