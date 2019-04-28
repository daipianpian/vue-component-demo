<template>
  <div>
    <p class="name" @click="nameClick(num)">{{name}}</p>
  </div>
</template>

<script>
  // import axios from 'axios';
  export default {
    data() {
      return {}
    },
    props: {
      name: {
        type: String
      }
    },
    methods: {
    },
    methods: {
      nameClick(num) {
        this.$emit('demoClick', num)
      }
    }
  }
</script>

<style scoped lang='scss'>
</style>