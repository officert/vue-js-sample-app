<template>
  <div id="app">
    <div class="message">
      {{ msg }}
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      msg: 'Hello from vue-loader!'
    }
  }
}
</script>

<style>
.message {
  color: blue;
}
</style>
