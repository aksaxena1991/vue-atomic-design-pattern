<template>
  
    <!-- <appGender/> -->
    
  <div>
    <AppSidebar :data="{filterObject}"></AppSidebar>
  </div>
</template>

<script>
// import appGender from '../molecules/appGender';
import AppSidebar from '../organisms/appSidebar';
export default {
  name: 'AtomsPage',
  data() {
    return {
      filterObject: [{
      heading:'Species',
      checkbox:[
        {
          value:true,
          label:'Human'
        },
        {
          value:true,
          label:'Mythology'
        },
        {
          value:true,
          label:'Other Species'
        }
      ]
    },
    {
      heading:'Gender',
      checkbox:[
        {
          value:true,
          label:'Male'
        },
        {
          value:true,
          label:'Female'
        }
      ]
    },{
      heading:'Origin',
      checkbox:[
        {
          value:true,
          label:'Unknown'
        },
        {
          value:true,
          label:'Nuptia'
        },
        {
          value:true,
          label:'Post-apocalptic earth'
        }
      ]
    }]
    }
  },
  components: {
    
    AppSidebar
  },
  mounted: () => {
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
