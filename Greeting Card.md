<html>
<head>
	<title>It's the New Year!</title>

</head>
<body style="background-color: Gold;">



<body>


<body> 
<h1>
<div id="champie1">
<pre>
*      *    .   *    .
     ..  *    o
   o   *  .    *
     ________
    (________)
    |    o   |
    | o    o |
    |   o    |
    | o    o |
    | o  o   |
    |      o |
    ( o      )
     \   o  /
      \    /
       \  /
        ||
        ||
        ||
        ||
        ||
     ___||___
    /   ||   \
    \________/
    </pre>
    </div>  </h1>

<h1>
<div id="champie2">
<pre>
*      *  .   *    .
**  o ..  *      o
 o *  .    o   *   .
     ________
    (________)
    |    o   |
    | o    o |
    |   o    |
    | o    o |
    | o  o   |
    |      o |
    ( o      )
     \   o  /
      \    /
       \  /
        ||
        ||
        ||
        ||
        ||
     ___||___
    /   ||   \
    \________/
    </pre>
    </div>  </h1>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.2.4/jquery.min.js"></script>
<script type="text/javascript">

  $("#champie1").hide();
  $("#champie2").hide();
  i = 1;
  function loop() {
    switch(i) {
      case 1:
        $("#champie2").hide();
        $("#champie1").show();
        i = 2;
        break;
      case 2: 
        $("#champie1").hide();
        $("#champie2").show();
        i = 1;
        break;
        
    }
  }
  loop();
  setInterval(loop, 1000);
  



</script>



<pre class="newYear">
   / /_  ____ _____  ____  __  __   ____  ___ _      __   __  _____  ____ ______
  / __ \/ __ `/ __ \/ __ \/ / / /  / __ \/ _ \ | /| / /  / / / / _ \/ __ `/ ___/
 / / / / /_/ / /_/ / /_/ / /_/ /  / / / /  __/ |/ |/ /  / /_/ /  __/ /_/ / /    
/_/ /_/\__,_/ .___/ .___/\__, /  /_/ /_/\___/|__/|__/   \__, /\___/\__,_/_/     
           /_/   /_/    /____/                         /____/                   
</pre>

    <script src="https://code.jquery.com/jquery-2.1.0.js"></script>
  <script>
  $(".newYear").hide();
  
    $("html").click(function (event) {
    $(".newYear").offset({
      left: event.pageX,
      top: event.pageY
    });
    $(".newYear").fadeOut(3000).fadeIn(3000);
  });
</script>
</body>



</body>
</html>
