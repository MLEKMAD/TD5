<template>
  <div style="width: 500px">
    <vs-navbar v-model="activeItem" class="nabarx">
      <div slot="title">
        <vs-navbar-title>
          TSE
        </vs-navbar-title>
      </div>

      <vs-navbar-item index="0">
        <a href="/">Home</a>
      </vs-navbar-item>
      <vs-navbar-item index="1">
        <a href="#">Counter</a>
      </vs-navbar-item>
      <vs-navbar-item index="2">
        <a href="#">Reverse Message</a>
      </vs-navbar-item>
    </vs-navbar>
  </div>
</template>
<script>
import Vue from "vue";
import { vsNavbar} from 'vuesax'
import 'vuesax/dist/vuesax.css'
 

Vue.use(vsNavbar);

export default {
  name: 'NavBar',
  data:()=>({
    activeItem: 0
  })
}
</script>

<style scoped>
@import url("https://fonts.googleapis.com/icon?family=Material+Icons");
@import url("https://cdn.jsdelivr.net/npm/vuesax/dist/vuesax.css");
</style>