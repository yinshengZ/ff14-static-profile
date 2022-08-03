<template>
    <div> 
        <div class="wrapper">
             <div class="profile-box">            
                <div class="player-profile">
                     <div class="profile-pic">                 
                        <img src="../assets/profile-pics/freya3.png" alt="Freya">                      
                     </div> 

                

                <div class="description">
                    <div class="tabs">
                        <n-tabs >
                            <n-tab-pane name="jobs" tab="Jobs">
                                <div class="jobs">
                                <span>PLD</span>
                                <span>MNK</span>
                                <span>WAR</span>
                                <span>DRG</span>
                                <span>SCH</span>
                                 </div>  
                            </n-tab-pane>

                            <n-tab-pane name="raids" tab="Raid Progress">
                                <div class="profile">                    
                        <p>Freya Arianrhod</p>
                        <p>Savage Progress: </p>
                        <ul>
                        <li>First Floor: Clear</li>
                        <li>Second Floor: Clear</li>
                        <li>Third Floor: Clear</li>
                        <li>Fourth Floor: Clear</li>
                    </ul>
                 </div>    
                            </n-tab-pane>
                        </n-tabs>
                    </div>
                     <div class="job-icons">
                        <img src="../assets/job-icons/Paladin.webp" alt="Paladin Icon">                       
                     </div>
                 
                
                </div>            
                </div>   
             
           
        </div> 
           <div class="profile-box">            
                <div class="player-profile">
                     <div class="profile-pic">                 
                        <img src="../assets/profile-pics/freya3.png" alt="Freya">                      
                        </div> 

                        
                <div class="description">
                     <div class="job-icons">
                        <img src="../assets/job-icons/Paladin.webp" alt="Paladin Icon">                       
                     </div>
                 <div class="profile">                    
                    <p>Freya Arianrhod</p>
                    <p>Savage Progress: </p>
                    <ul>
                        <li>First Floor: Clear</li>
                        <li>Second Floor: Clear</li>
                        <li>Third Floor: Clear</li>
                        <li>Fourth Floor: Clear</li>
                    </ul>
                 </div>    
                
                </div>            
                </div>   
             
           
        </div> 
           <div class="profile-box">            
                <div class="player-profile">
                     <div class="profile-pic">                 
                        <img src="../assets/profile-pics/freya3.png" alt="Freya">                      
                        </div> 

                        
                <div class="description">
                     <div class="job-icons">
                        <img src="../assets/job-icons/Paladin.webp" alt="Paladin Icon">                       
                     </div>
                 <div class="profile">                    
                    <p>Freya Arianrhod</p>
                    <p>Savage Progress: </p>

                    <ul>
                        <li>First Floor: 
                            <div class="progress-bar">
                                <n-progress
                            type="line"
                            indicator-placement="inside"
                            color ="orange"
                            :percentage="100"
                            processing></n-progress>
                            </div>
                            
                        </li>

                        <li>Second Floor:
                             <div class="progress-bar">
                                <n-progress
                            type="line"
                            indicator-placement="inside"
                            
                            :percentage="100"
                            processing></n-progress>
                            </div>
                        </li>
                        <li>Third Floor: 
                             <div class="progress-bar">
                                <n-progress
                            type="line"
                            indicator-placement="inside"
                            
                            :percentage="100"
                            processing></n-progress>
                            </div>
                        </li>
                        <li>Fourth Floor: 
                             <div class="progress-bar">
                                <n-progress
                            type="line"
                            indicator-placement="inside"
                            
                            :percentage="100"
                            processing></n-progress>
                            </div>
                        </li>
                    </ul>
                 </div>    
                
                </div>            
                </div>   
             
           
        </div> 
           <div class="profile-box">            
                <div class="player-profile">
                     <div class="profile-pic">                 
                        <img src="../assets/profile-pics/freya3.png" alt="Freya">                      
                        </div> 

                        
                <div class="description">
                     <div class="job-icons">
                        <img src="../assets/job-icons/Paladin.webp" alt="Paladin Icon">                       
                     </div>
                 <div class="profile">                    
                    <p>Freya Arianrhod</p>
                    <p>Savage Progress: </p>
                    <ul>
                        <li>First Floor: Clear</li>
                        <li>Second Floor: Clear</li>
                        <li>Third Floor: Clear</li>
                        <li>Fourth Floor: Clear</li>
                    </ul>
                 </div>    
                
                </div>            
                </div>   
             
           
        </div> 
    </div>       
        
           

     </div> 

        



</template>

<script>

</script>

<style scoped>
body{
 background-color:aquamarine;
}
.wrapper{
    display:flex;
    justify-content: center;
    height:100%;
   
    outline:auto;
}
.profile-box{
    display:inline-block;
    outline:auto;
    width:12%;
    height:100%;
    overflow:hidden;
    position:relative;    
    transition: width 2s, height 2s;
    transform:skew(4deg);
    

    
    
}

.profile-pic> img{
    margin-left: -250px;
    transition: margin-left 2s;
}

.profile-box:hover{
     
    object-fit: cover;
    width:50%;
    height:100%;

 }
 .profile-pic > img:hover{
    margin-left: 0px;
    
 }

 .profile {
    color:white;
   
 }

.progress-bar{
    width:70%;
    display:inline-block;
    
}
.description{
    position: absolute;
    top:300px;
    left:300px;
    width:600px;
    height:363px;
    background: rgba(1, 25, 31, 0.884);
    transform:skew(-4deg);

}
.description .tabs{
    margin-left:20%;
    color:red;
}

.jobs{
    position:absolute;
    top:700px;
    left: 50px;
    width:300px;
    height: 200px;
    background:rgba(88, 135, 146, 0.5);
}



</style>
