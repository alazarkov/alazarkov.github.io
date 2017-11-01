# wow


dfsdf

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>
<style>
  div.background {
    background: url(banner.jpg) repeat;
    border: 2px solid black;
  }

  div.transbox {
    margin: 30px;
    background-color: #ffffff;
    border: 1px solid black;
    opacity:0.6;
    filter:alpha(opacity=60); 
    width: 200px;
    height: 500px;
  }

  div.transbox p {
    margin: 5%;
    font-weight: bold;
    color: #000000;
  }
  #animation{font-size:20px; margin-top:40px; margin-left:50px;}
</style>

<script>

function loadImage() {
    $("#animation").animate({ marginTop: "300px" }, 1500 ).animate({ marginBottom: "40px" }, 800 );
}


</script>


<div onload="loadImage()">
    <div class="background">
      <div class="transbox" id="animation">
          <p>Text to fly in</p>
       </div>
    </div>

</div>
