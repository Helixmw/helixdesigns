<template>
  <div>

    <div class="footer">
      <div class="notes">
        
        <div class="note spacing">This landing page is merely for portfolio purpose. If you'd like to know about our development packages. click on 'Main Site'</div>
        <div class="note2 spacing">Designed by &nbsp; <a href="https://www.linkedin.com/in/wongani-chipofya-896106221/" target="_blank">Wongani Chipofya</a></div>
      </div>
      <div class="bottom">
        <div class="box2 link_">
          <div class="link">www.helixdesignsmw.com</div>
        </div>
        <div class="box2 link_">
          <div class="link"></div>
        </div>
        <div class="box2 link_"><img src="../assets/black.png" alt=""></div>
        </div>
      </div>
      <div class="footer2">
        <div class="top">This landing page is merely for portfolio purpose. If you'd like to know about our development packages. click on 'Main Site'</div>
        <div class="middle">
          <div class="label">
            <div class="lbl lbl1">DESIGNED BY</div>
            <div class="lbl lbl2"><a href="https://www.linkedin.com/in/wongani-chipofya-896106221/" target="_blank">Wongani Chipofya</a></div>
        </div>
        </div>
        <div class="down">
         <img src="../assets/black.png" alt="" class="small-img">
        </div>
      </div>

    </div>
  
  </template>
  
  <script>
  export default {
  
  }
  </script>
  
  <style scoped>

  .link_{
    display: flex;
    justify-content: center;
    align-items: flex-end;
  }

  .link{
    font-weight: bold;
    font-size:1.3rem;
  }
  img{
    height: 8rem;
  }

  .bottom{
    padding-top:1.2rem;
    display: flex;
    justify-content: space-between;
    opacity: 0.5;
  }

  .box2{
    flex:1;
    
  }

  a{
    text-decoration:none;
    font-weight: bold;
   color:rgb(128, 180, 240);
  }

  .spacing{
    margin-left:1.2rem;
    margin-bottom:1.4rem;
  }

  .notes{
    display:flex;
    flex-direction: column;
  }

  .small{
    height:4rem;
  }
  .note{
    font-family: Raleway;
    font-size:1.1rem;
    height:8rem;
    width:20rem;
    border-left:5px solid rgb(128, 180, 240);
    display: flex;
    align-items: center;
    padding:0.5rem;
  }
  .note2{
    font-family: Raleway;
    font-size:1.1rem;
    height:3rem;
    width:20rem;
    border-left:5px solid rgb(128, 180, 240);
    display: flex;
    align-items: center;
    padding:0.5rem;
  }
  .footer{
    background-image: url('../assets/bg.png');
    height:29rem;
  }

  .footer2{
    display:none;
  }

  @media screen and (max-width: 768px){
    .footer{
    display: none;
  }

  .footer2{
    display: block;
    height:13rem;
    
  }
  .down{
    background-image:url('../assets/bg4.png');
    height:13rem;
    
    
    
  }

  .top{
    text-align:center;
    margin-left:3rem;
    margin-right:3rem;
    margin-top:3rem;
    margin-bottom:6rem;
   
    width:70%;
    font-family:Raleway;
    padding-left:0.4em;
    padding-right:0.4em;
    border-left:3px solid rgba(46, 133, 214, 0.568);
    border-right:3px solid rgba(46, 214, 130, 0.568);
    /* linear-gradient(90deg,rgba(46, 133, 214, 0.568),rgba(46, 214, 130, 0.568) ) */

  }

  .label{
    text-align: center;
    margin-right:0.5em;
    color:rgb(146, 145, 145);
    font-family: Raleway;
  }

  .lbl1{
    letter-spacing:0.2rem;
    font-size:0.7em;
    margin-bottom:0.2em;
  }

  .lbl2{
    font-weight: bold;
  }

  .small-img{
    height:6rem;
    opacity:0.6;
    margin-top:5rem;
    margin-left:1.4rem;
  }

  }
  </style>