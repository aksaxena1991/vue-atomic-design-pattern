<template>
  
    <!-- <appGender/> -->
    
  <div>
    <AppSidebar :data="{filterObject}"></AppSidebar>
    <AppTopbar/>
    <AppContent/>

  </div>
</template>

<script>
import AppTopbar from '../organisms/AppTopbar';
import AppSidebar from '../organisms/AppSidebar';
import AppContent from '../organisms/AppContent';
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
    AppTopbar,
    AppSidebar,
    AppContent
  },
  mounted: () => {
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
