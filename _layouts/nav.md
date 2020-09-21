<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ page.title }}</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script> 
    <script>
      // detect IE8 and above, and edge
      if (document.documentMode || /Edge/.test(navigator.userAgent)) {
          alert('Please use Chrome or Firefox for best browsing experience!');
      }
    </script>
  
    <!-- load CSS -->
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Open+Sans:300,400">  <!-- Google web font "Open Sans" -->
    <link rel="stylesheet" href="css/bootstrap.min.css">                                      <!-- https://getbootstrap.com/ -->
    <link rel="stylesheet" href="css/fontawesome-all.min.css">                                <!-- Font awesome -->
    <link rel="stylesheet" href="slick/slick.css">
    <link rel="stylesheet" href="slick/slick-theme.css">
    <link rel="stylesheet" href="css/templatemo-style.css">
   
    <link rel="stylesheet" href="index.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">
  </head>
  <body style="background-color: rgba(235, 194, 216, 0.788);">
    <nav class="navbar navbar-expand-md navbar-dark mx-auto" style="background-color: rgba(34, 32, 34, 0.658);" >
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
    
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto mx-auto">
          <li class="nav-item mx-auto " style="width: 100px;">
            <a class="nav-link font-weight-bold" href="/" >Home </a>
          </li>
          <li class="nav-item mx-auto " style="width: 100px;">
            <a class="nav-link font-weight-bold" href="/contact" >Contact</a>
          </li>
          <li class="nav-item mx-auto" style="width: 100px;">
            <a class="nav-link font-weight-bold" href="../templatemo_519_beauty/index.html" >Blog</a>
          </li>
        </ul>
      </div>
    </nav>
    {{ content }}
  </body>
</html>