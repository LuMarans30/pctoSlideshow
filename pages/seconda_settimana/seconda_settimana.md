---
transition: slide-up
---

# Seconda settimana

All'inizio della seconda settimana ho terminato il progetto riguardante la documentazione delle API, e ho iniziato a lavorare su un progetto riguardante il frontend di un sito web.<br />
Mi è stato chiesto di implementare un pulsante per la ricerca di un record tramite una tabella di dati.<br />

<div style="display: flex; flex-direction: row; gap: 70px">

<div style="width: 30vh; height: 20vh;" >
<div class="container">
    <span  class="react-logo">
        <span class="nucleo"></span>
    </span>

</div>
    <p class="title">React</p>
</div>
<img 
    style="width: 60vh; height: 40vh;" 
    src="https://cdn.syncfusion.com/content/images/company-logos/Syncfusion_Logo_Image.png"/>
</div>

<style>

  .container{
    width:250px;
    height:250px;
    margin:20px auto 0 auto;

    display:flex;
    align-items: center;
    justify-content: center;
  }

  .react-logo{
    display: inline-block;
    border-radius:50%;
    border:10px solid #00d8ff;

    animation-name:rotate;
    animation-duration: 10s;
    animation-iteration-count: infinite;
    animation-timing-function: linear;

  }

  .react-logo , .react-logo:before , .react-logo:after{
    position:absolute;
    display: inline-block;
    width:200px;
    height:70px;
    border-radius:50%;
    border:10px solid #00d8ff;
  }

  .nucleo , .react-logo , .react-logo:before , .react-logo:after {
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .nucleo{
    width:40px;
    height:40px;
    border-radius:100%;
    background:#00d8ff;
  }

  .react-logo:before , .react-logo:after{
    content:"";
  }

  .react-logo:after{
    transform:rotate(-57deg);
  }

  .react-logo:before{
    transform:rotate(57deg);
  }
  
.title{
  font-size:60px;
  color:#00d8ff;
  width:250px;
  margin:2px auto;
  text-align:center;
}

  @keyframes rotate{

    100%{
      transform:rotate(360deg);
    }
  }


</style>