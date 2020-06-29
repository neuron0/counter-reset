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
 body.style.backgroundColor = "red";
 change();
}
  function change(){
  count += 1;
  c=document.getElementById('counter');
   c.innerHTML=`<h1>${count}</h1>`;
  }

  function reset(){
    count = 0;
    c=document.getElementById('counter');
    c.innerHTML=`<h1>${count}</h1>`;
  }
</script>
  </head>
  <body id="root">
@@ -27,6 +33,7 @@
    <div id="counter">
    </div>
    <button type="button" name="button" onclick=changemain()>click here</button>
    <button type="button" name="button" onclick="reset()">RESET</button>
    </div>
    </center>
  </body>
