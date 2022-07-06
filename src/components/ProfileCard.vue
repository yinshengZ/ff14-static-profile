<template>
    <div>
        <header>
            <span class="player_name">Freya Arianrhod</span>
        </header>
        <div class="container card">
            <div class="inner">
                  <h2 class="description">
                <span class="description">Paladin</span>
                </h2>
            </div>
          


        

      
            

        </div>
        
    </div>
</template>

<script>
</script>

<style scoped>
.card{
    height:400px;
    width:700px;
    position:relative;
    padding:20px;
    box-sizing:border-box;
    display:flex;
    align-items: flex-end;
    text-decoration:none;
    border:4px solid #b0215e;
    margin-bottom:20px;
    background-image: url('../assets/profile-pics/Freya.png');
    background-size:700px 400px ;

}

.inner{
    height:50%;
    display:flex;
    flex-direction:column;
    justify-content:center;
    background:white;
    box-sizing:border-box;
    padding: 80px;
    margin-bottom:100px;
}

.description :hover{
    color:blue;
}
</style>