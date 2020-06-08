<template>
  <button :type="{type}">{{label}}
  </button>
</template>

<script>
export default {
  name: 'AppButton',
  data () {
    return {}
  },
  props: {
    label: String,
    type:String
  }
}
</script>

<style scoped>

</style>
