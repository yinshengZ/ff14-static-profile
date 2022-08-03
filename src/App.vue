<template>
 
 <div>


  <profile-box></profile-box>
 </div>
  
</template>

<script>
import ProfileBox from './components/ProfileBox.vue'


export default {
  name: 'App',
  components: {
    //ProfileCard,
    ProfileBox
  }
}
</script>

<style>

body{
margin:25px;
background-color:rgba(0, 6, 32, 0.897);
}

</style>
