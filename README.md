<!DOCTYPE html>
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title></title>
<script>
  var c;
  var count = 0;

function changemain(){
 var body = document.getElementById('root');
@@ -14,8 +15,9 @@
}

  function change(){
  count += 1;
  c=document.getElementById('counter');
   c.innerHTML="<h1>hello</h1>";
   c.innerHTML=`<h1>${count}</h1>`;
  }
</script>
  </head>
  <body id="root">
    <center>
    <div class="#">
    <div id="counter">
    </div>
    <button type="button" name="button" onclick=changemain()>click here</button>
    </div>
    </center>
  </body>
</html>
