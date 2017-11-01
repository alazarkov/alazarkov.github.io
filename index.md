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
    var dWidth = $(document).width() - 100, // 100 = image width
      dHeight = $(document).height() - 100, // 100 = image height
      nextX = Math.floor(Math.random() * dWidth),
      nextY = Math.floor(Math.random() * dHeight);
    $(this).animate({
      left: nextX + 'px',
      top: nextY + 'px'
    });
  });
});


</script>

<div style="height:100px; width:100px; background:#090909">
<img src="/facepalm.jpg" width="100" height="100" alt="Grey Square" id="img" />

<input type="submit" value="Отправить" onclick="loadImage()">
</div>
