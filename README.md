<html>
<head>
  <title>Change bg color every 1 seconds</title>
</head>
<body>
<h1>Background Color is being changed every 1 seconds</h1>
<script>
setInterval(
function () {
  var randomColor = Math.floor(Math.random()*16777215).toString(16);
  document.body.style.backgroundColor = "#"+randomColor;
},1000);
</script>
</body>
</html>
# back-ground-colour-changer
