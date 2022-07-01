<template>
    <div>
        <n-grid x-gap="50" :cols="4">
            <n-gi>
                  <n-card  class="profile-card" title="Paladin">
                   <template #cover>
                    <img src="../assets/profile-pics/Freya.jpg" alt="Freya">
                   </template> 

                   Freya Arianrhod
                    
                  </n-card>
            </n-gi>

            <n-gi>
                <n-card>
                    Player 2
                </n-card>
            </n-gi>

            <n-gi>
                <n-card>
                     Player 3
                </n-card>
               
            </n-gi>
            
            <n-gi>
                <n-card>Player 4</n-card>
                
            </n-gi>

        </n-grid>
      
    </div>
</template>

<script>

</script>

<style scoped>
.profile-card{
    background-color:transparent;
    outline:auto;
}
</style>
