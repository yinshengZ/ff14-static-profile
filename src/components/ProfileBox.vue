<template>
    <div>        
         <div class="profile-box">            
                   
                <div class="profile-pic">                 
                        <img src="../assets/profile-pics/freya2.png" alt="Freya">
                        <div class="character-name">Freya Arianrhod</div>
                </div> 
                <div class="description">
                     <div class="job-icons">
                        <img src="../assets/job-icons/Paladin.webp" alt="Paladin Icon"> 
                      
                     </div>
                 <div class="profile">
                    
                    <p>Freya Arianrhod</p>
                 </div>    
                
                </div>                
        </div> 


    </div>
</template>

<script>

</script>

<style scoped>
.profile-box{
    display:flex;
    outline:auto;
    width:90px;
}
.profile-pic{
    position:relative;
    text-align: center;
    color:rgb(1, 24, 8);
    outline:auto;
    max-width:min-content;
}

.description{
    max-width:600px;
    height:363px;
    display:none;

}

.character-name{
    position:absolute;    
    left:50%;
    transform:translate(-50%,-2000%);
    
}


</style>
