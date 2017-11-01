# wow11




<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>
<style>
#flying_object {
  position: relative;
}

</style>

<script>
function move1() {
    var dWidth = $('#field').width() - 100,
      dHeight = $('#field').height() - 100,
      nextX = Math.floor(Math.random() * dWidth),
      nextY = Math.floor(Math.random() * dHeight);
    $(this).animate({
      left: nextX + 'px',
      top: nextY + 'px'
    });
  }
  
jQuery(function($) {
  $('#flying_object').mouseover(move1);
});


</script>

<div style="height:400px; width:600px; background:#A0A0A0; min-height: 400px; min-width: 600px;" id="field">
  <div id="flying_object">
    <img src="facepalm.jpg" width="100" height="100" alt="Grey Square" />
    <p>Сашка</p>
  </div>

</div>



## Some links

[flying text](http://jsfiddle.net/karalamalar/atNva/)
