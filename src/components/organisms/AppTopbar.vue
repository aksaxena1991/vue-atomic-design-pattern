<template>
  <div>
    <AppCancelbar/>
    <AppSearchItem/>
  </div>
</template>

<script>
import AppSearchItem from '../molecules/AppSearchItem';
import AppCancelbar from '../molecules/AppCancelbar';
export default {
  name: 'AppTopbar',
  data () {
    return {}
  },
  components: {
    AppSearchItem,
    AppCancelbar
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
