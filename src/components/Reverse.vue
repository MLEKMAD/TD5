<template>
  <div class="reverse">
      <h3>{{msg}}!</h3>
<button v-on:click="msg = msg.split('').reverse().join('')">reverse</button>  </div>
</template>

<script>
export default {
  name: 'reverse',
  data () {
    return {
      msg:'HELLO WORLD'
    }
  }
}
</script>