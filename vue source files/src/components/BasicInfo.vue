<template>
  <div class="info">
    <div class="box box_">
        <div class="heading left_">PROFESSIONAL</div>
        <div class="words ">Software design work by Helix Designs guarantees you the best looking Web Software to give your visiting clients a professional appearance to your online service.</div>
    </div>
    <div class="box box_">
        <div class="heading middle_">UP-TO-DATE</div>
        <div class="words">
            Development utilizes industry-standard software development practices with adequate testing and security consideration. Design
is what we love but data security remains a top priority.
        </div>
        </div>
    <div class="box box_">
        <div class="heading right_">CLIENT FIRST</div>
        <div class="words">
            We love to listen to the kind of finished work our customers envision, and aim to aquire adequate information on software requirement as a solid road map to meet our customers needs.</div>
        </div>
    </div>

</template>

<script>
export default {

}
</script>

<style scoped>
.info{
    display:flex;
    justify-content:space-between;
    padding-left:8%;
    padding-right:8%;
    margin:1rem;
}
.heading{
    background-color: aqua;
    width:100%;
    padding:0.3rem;
    margin-bottom:0.4rem;
    
}

.left_{
    background-color: rgba(46, 133, 214, 0.568);
}

.right_{
    background-color: rgba(46, 214, 130, 0.568)  
}

.middle_{
    background-color: rgba(46, 133, 214, 0.568);
    background:linear-gradient(90deg,rgba(46, 133, 214, 0.568),rgba(46, 214, 130, 0.568) );
}

.left_, .middle_, .right_{
    color:white;
    font-family: Gobold;
    letter-spacing:0.2rem;
}

.words{
    line-height:1.4rem;
    font-family: Raleway;
    
}

.box{
    flex:1;
    margin:0.8rem;

}

@media screen and (max-width: 768px){

    /* .words{
        font-size: 1.2em;
    } */
    .info{
    display:flex;
    flex-direction: column;
    padding-left:1%;
    padding-right:1%;
    margin:0.1rem;
}

.box_{
    margin-top:2rem;
}


}

</style>