<template>
  <div class="cards cards2">
    <div class="set set1">
      <div class="box_ frame">
        
        <div class="card2 img1"></div>
      </div>
      <br/>
        <div class="box_ card1 spaced aligning">Here at Helix Designs we are passionate about our work. And work to provide our clients with only the best custom-made Web Products as we strive to become a dependable name on the Web Development market.</div>
        
    </div>
    <div class="set set2">
      <div class="box_ frame">
        
        <div class="card2 img2"></div>
      </div>
      <br/>
        <div class="box_ card1 aligning">We listen and build in a way that brings our clients' vision to life. And maintain client relationships while doing our work with integrity and respect for confidentially with our clients.</div>
        
    </div>
    <div class="set set1">
      <div class="box_ frame">
        
        <div class="card2 img3"></div>
      </div>
      <br/>
        <div class="box_ card1 spaced aligning">In order to provide the best we hire the best. With a team of graphic designers and developers driving the engine of our operations to produce high standard Web Software products.</div>
        
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

.cards{
  display:flex;
  flex-direction: column;
  align-items: center;
}

.img1{
  background-image: url('../assets/1.png');
  background-size:cover;
}
.img2{
  background-image: url('../assets/2.jpg');
  background-size:cover;
}
.img3{
  background-image: url('../assets/3.jpg');
  background-size:cover;
}

.spaced{
  margin-left:0.5rem;
}

.set2{
  flex-direction: row-reverse;
}

.card1{
    padding:1rem;
    font-family: Raleway;
    font-size:1.2rem;
    line-height:1.4rem;
    height:11rem;
    width:27rem;

}

.card2{
    background-color:green;
    
    height:16rem;
    width:16rem;
    border-radius:100%;
}

.frame{
    border:0.2em rgb(20, 80, 99) dashed;
    display: flex;
    justify-content: center;
    align-items: center;
    height:17rem;
    width:17rem;
    border-radius:100%;
}

.set{
  display:flex;
  align-items: center;
  margin:1rem;
}

@media screen and (max-width: 768px){

  .card2{
    background-color:green;
    
    height:7em;
    width:7em;
    border-radius:100%;
}

.frame{
    border:0.2em rgb(20, 80, 99) dashed;
    display: flex;
    justify-content: center;
    align-items: center;
    height:7em;
    width:7em;
    border-radius:100%;
}

.card1{
    padding:0.5rem;
    font-family: Raleway;
    font-size:1em;
    line-height:1.4em;   

}

.aligning{
  padding-top:3em;
}

.cards{
 margin:0.5rem;
}

.cards2{
  margin-top:-0.8rem;
}

.set{
  width:100%;
  margin:1rem;
}


}





</style>