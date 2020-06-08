<template>
  <button :type="{type}">{{label}} <span v-on:click="clickHandler">X</span>
  </button>
</template>

<script>
export default {
  name: 'AppCrossButton',
  data () {
    return {}
  },
  props: {
    label: String,
    type:String
  },
  methods: {
    clickHandler() {
      console.log("It is clicked");
    }
  }
}
</script>

<style scoped>
</style>
