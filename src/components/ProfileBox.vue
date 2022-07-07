<template>
    <div class="profile-box">

        <div class="center">
            <div class="player">

             <div class="player1">
                <img src="../assets/profile-pics/1.jpg" alt="">
             </div>

             <div class="player2">
                <img src="../assets/profile-pics/player2.webp" alt="">
                <div class="description">
                    <p>Name</p>
                    <p>Team leader with call outs and tanking!</p>
                    <p>savage progress:</p>
                    <ul>
                        <li>P1S: Cleared!</li>
                        <li>P2S: Cleared!</li>
                        <li>P3S: Cleared!</li>
                        <li>P4S: Cleared!</li>
                    </ul>
                </div>
             </div>

             <div class="player3">
                <img src="../assets/profile-pics/3.jpg" alt="">
             </div>

             <div class="player4">
                <img src="../assets/profile-pics/4.jpg" alt="">
             </div>

            </div>

        </div>

    </div>
</template>

<script>
    export default{
        data(){
            return{

            }
        },

        methods:{
            enlarge(){
                alert('clicked!')
            }
        }
    }
</script>

<style scoped>

.profile-box{
    display:flex;    
    outline:auto;   
    width:1270px;
    height: 720px;   

}
.center{
    width:800px;
    height:350px;
    margin:auto auto;
    outline:auto;
}

.player{
    width:800px;
    height:350px;
    display:inline-block;
}
.player1{
    background-image:url(../assets/profile-pics/Freya.jpg);
    width:25%;
    height:100%;
    background-repeat:no-repeat;
    display:inline-block;
}
.player1 img{
    width:100%;
    height:100%;
}

.player2{
    
    width:25%;
    height:100%;
    display:inline-block;
}
.player2 img{
    width:100%;
    height:100%;
    margin:auto auto;
    
}

.player2 .description{
    display:none;
}
.plaer2 .description :hover{
    display:inline-block;
}
.player2 img + .description :hover {
    width:200%;
    display:inline-block;
    filter:blur(4px);    
}


.player3{
    width:25%;
    height:100%;
    display:inline-block;
}

.player3 img{
    width:100%;
    height:100%;
}

.player4{
    width:25%;
    height:100%;
    display:inline-block;
}

.player4 img{
    width:100%;
    height:100%;
}

img{
    border-radius:8px;
}

</style>
