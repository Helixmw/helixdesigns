
<template>
  <div class="welcome">
    <div class="filter">
        <div class="container-1">
            <div class="box">
                <div class="container-2">
                    <div class="box_ big">Welcome to the world of quality web design</div>
                    <div class="box_ small">We're excited to show you what we do!</div>
                    <br/>
                    <br/>
                    <a href="http://helixdesignsmw.com/" target="_blank" class="button">{{label}}</a>
                </div>
            </div>
            <div class="box"><img src="../assets/HELIX-DESIGNS5.png" alt="" class=""></div>   
        </div>
        <div class="container-3">
            <div class="box2 big">Welcome to the world of quality web design</div>
            <div class="box2 small">We're excited to show you what we do!</div>
            <div class="box2 button">{{label}}</div>
            <div class="box2 image"><center><img src="../assets/HELIX-DESIGNS5.png" alt="" class="img_"></center></div>
        </div>
    </div>
    </div>
  
</template>

<script>
export default {
    data(){
        return{
            label: "Official Site"
        }
    }
}
</script>

<style scoped>

.button{
    margin-top:6rem;
    border:2px solid white;
    padding:0.6rem;
    border-radius:3px;
    text-align: center;
    width:7rem;
    cursor: pointer;
    text-decoration: none;
    color:white;
}

.button:hover{
    background-color: rgb(255, 255, 255);
    color:rgb(84, 166, 243);
}

.img{
    height:27rem;
}

.filter{   
    left:0;
    right:0;
    height:100%;
    background-color: rgba(46, 133, 214, 0.568);
    background:linear-gradient(90deg,rgba(46, 133, 214, 0.568),rgba(46, 214, 130, 0.568) )
}

.small{
    font-size:1.3rem;
}

.big{
    font-size:2rem;
    width:23rem;
    margin-bottom:0.7rem;
}

.big,.small{
    font-family: Raleway;
}



.container-2, img{
    margin-top:4rem;
    color:white;
}
.container-3{
    display: none
}
.welcome{
    width:100%;
    height:27rem;
    background-image:url('../assets/bg1.jpg');
    background-size: cover;
    
}
.container-1{
    display: flex;
    justify-content: flex-end;
    align-items: center;
    position: relative;
    width:100%;

}

.box{  
    width:40rem;   

}

@media screen and (max-width: 768px){
    .container-1{
        display: none;
    }
    .button{
        margin-top:1rem;
    }
    .big{font-size:1.8rem;}
    .small{font-size:1rem;}

    .image{
        display: flex;
        justify-content: space-around;
    }
    .img_{
        height:8rem;
        
    }
    .container-3{
        display:block;
        color:white;
        justify-content: center;
        margin:0.7rem;
        padding-top:7rem;
    }


    .welcome{
        height:32rem;
       
    }
}




</style>