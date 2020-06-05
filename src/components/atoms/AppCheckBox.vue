<template>
  
     <md-checkbox v-model="model" v-bind:value="{value}">{{label}}</md-checkbox>
  
</template>

<script>
export default {
  name: 'AppCheckbox',
  data(){
    return{
      model:[]
    }
  },
  props: {
    
    value:Boolean,
    label:String
  },
  mounted() {
    
    // console.log('anubhav saxena',this);
  }
}
</script>
<style lang="scss" scoped>
  .md-checkbox {
    display: flex;
  }

  table {
    width: 100%;
    table-layout: fixed;

    th {
      text-align: left;
    }
  }
</style>
