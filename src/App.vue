<script >
  import NavBar from './components/partials/NavBar.vue';
  export default{
    components:{
      NavBar
    }
  }

</script>

<template>
  <div class="container">
    <NavBar />
    <router-view></router-view>
  </div>
  
</template>




<style scoped>

</style>
