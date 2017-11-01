# Junior software developer

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
    }, );
  }
  
jQuery(function($) {
  $('#flying_object').mouseover(move1);
});


</script>

<div style="height:400px; width:600px; background:#FFFFFF; min-height: 400px; min-width: 600px;" id="field">
  <div id="flying_object" width="200px" height="200px">
    <span class="p-0" >
      <img src="facepalm.jpg" width="100" height="100" alt="Grey Square" />
      <p class="text-center">Сашка - учи программирование!</p>
      <p class="text-center"> <a>Нажми сюда</a></p>
    </span>
  </div>

</div>



## Some links

* [flying text](http://jsfiddle.net/karalamalar/atNva/)
* [more](http://jsfiddle.net/3Z7HE/3/)
* [and more](http://jsfiddle.net/Xw29r/15/)

