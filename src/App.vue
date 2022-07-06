<template>
 
 <div>
  <profile-card>
    
  </profile-card>

  <profile-box></profile-box>
 </div>
  
</template>

<script>
import ProfileBox from './components/ProfileBox.vue'
//import ProfileCard from './components/ProfileCard.vue'

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
background-color:#F6F4F9;
}

</style>
