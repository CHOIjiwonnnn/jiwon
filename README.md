<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>JS Bin</title>
  <script>
function change(){
    var d= new Date();
    var h= d.getHours();
     var len=document.getElementsByTagName("h1").length;
     alert(len);
     for (var i=0;i<len;i++){
    document.getElementsByTagName("h1")[i].style.color="coral";
     }
    
   }   
    </script>
</head>
<body>
  <h1 onclick="change()">test</h1>
  <h1>test</h1>
  <h1>test</h1>
  <h1>test</h1>
  <h1>test</h1>
  <h1>test</h1>
  <h1>test</h1>
  <h1>test</h1>
 
</body>
</html>
