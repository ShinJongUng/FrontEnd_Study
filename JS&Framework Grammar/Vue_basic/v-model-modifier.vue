<template>
  <h1>{{msg}}</h1>
  <input type="text" v-model.trim="msg">
</template>
  

<script>
export default {
  data() {
    return {
      msg: 'hello world'
    }
  },
  methods: {
  
  },
  watch: {
    msg() {
      console.log(this.msg)
    }
  }
}
</script>
