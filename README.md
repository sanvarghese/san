
<!doctype html>
<html>

<head>
   <title>jQuery-add-elements</title>
   <script src="https://www.tutorialspoint.com/jquery/jquery-3.6.0.js"></script>
   <script>
      $(document).ready(function () {
         $("button").click(function () {
            $(".inner").append("<h3>Elements</h3>");
            $("<p>append</p>").appendTo(".content");
            $(".content-2").after("<button>after</button>");
            $(".content-3").prepend("<p>prepend</p>");
            $("<p>san</p>").prependTo(".content-4");
            $(".content-5").before("<p>Zara</p>");

         });
      });
   </script>
</head>

<body>

   <button>Add Text</button>

   <div class="container">
      <h2> append</h2>
      <div class="inner">Hello</div>
      <div class="inner">Goodbye</div>
   </div>
   <br>

   <div class="container">
      <h2>appendTo</h2>
      <div class="content">Hello</div>
      <div class="content">Goodbye</div>
   </div>

   <h2>after</h2>
   <div class="content-2">Hello</div>
   <div class="content-2">Goodbye</div>

   <h2>prepend</h2>
   <input class="content-3" test="this is test" type="text" name="txtname" data-address="wayanad kerala">


   <h2>prependTo</h2>
   <!-- <input class="content-4" test="this is test" type="password" name="txtname" data-address="wayanad kerala"> -->
   <div class="content-4">Goodbye</div>

   <h2>before</h2>
   <div class="inner">Hello</div>
   <div class="inner">Goodbye</div>
   <input class="content-5" test="this is test" type="time" name="txtname" data-address="wayanad kerala">


</body>

</html>
