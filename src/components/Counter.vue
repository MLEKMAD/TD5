<template>
  <div class="hello">
  <button v-on:click="count++">You clicked me {{ count }} times.</button>
  </div>
</template>

<script>
export default {
  name: 'counter',
  data () {
    return {
      count:0
    }
  }
}
</script>