<template>
  <div id="header">
    <h1>{{ msg }}</h1>
    
  </div>
</template>

<script>
export default {
  name: 'Header',
  data () {
    return {
      msg: '头部'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
