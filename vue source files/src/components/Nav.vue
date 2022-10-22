<template>
    <div class="nav">
        <img src="../assets/logo.png" class="icons left"/>
    </div>
</template>
<style scoped>
.nav{
    position:fixed;
    left:0;
    top:0;
    right:0;
    background-color:rgba(255, 255, 255, 0.6);
    backdrop-filter: blur(2px);
    display:flex;
    height:3.4rem;
}

.icons{
        
        margin:0.3rem;      
    }

    .left{
        margin-left:0.7rem;
    }

@media screen and (max-width: 768px){
    .nav{
        height:3rem;
    }

    .left{
        margin-left:0.8rem;
    }

    
}
</style>