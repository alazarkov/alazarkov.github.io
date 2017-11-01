# wow11


## Some links

[flying text](http://jsfiddle.net/karalamalar/atNva/)

end.

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>
<style>
#img {
  position: relative;
}

</style>

<script>

jQuery(function($) {
  $('#img').mouseover(function() {
    var dWidth = $('#field').width() - 100, // 100 = image width
      dHeight = $('#field').height() - 100, // 100 = image height
      nextX = Math.floor(Math.random() * dWidth),
      nextY = Math.floor(Math.random() * dHeight);
    $(this).animate({
      left: nextX + 'px',
      top: nextY + 'px'
    });
  });
});


</script>

<div style="height:400px; width:400px; background:#A0A0A0; min-height: 400%; min-width: 400%;" id="field">
<img src="/facepalm.jpg" width="100" height="100" alt="Grey Square" id="img" />

<input type="submit" value="Отправить" onclick="loadImage()">
</div>
