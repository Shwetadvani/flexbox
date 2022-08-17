# flexbox
<html>
<head>
  <script> src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js" </script>
<script>
$(document).ready(function(){
  $("button").click(function(){
    $("#div1").fadeOut();
    $("#div2").fadeOut("slow");
    $("#div3").fadeOut(3000);
  });
});
</script>
</head>
<body>

<p>Demonstrate fadeOut() with different parameters.</p>

<button>Click to fade out boxes</button><br><br>

<div id="div1" style="width:100px;height:100px;background-color: indigo;"></div><br>
<div id="div2" style="width:100px;height:100px;background-color:hotpink;"></div><br>
<div id="div3" style="width:100px;height:100px;background-color:lightgreen;"></div>

</body>
</html>
