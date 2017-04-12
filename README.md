<!DOCTYPE html>
<html>
<head>
  <title>Dess Design | Website with Scroll Spy</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.0/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  <style>
  body {
      position: relative; 
  }
  #section1 {padding-top:50px;height:500px;color: #fff; background-image: url("images/image1.jpg");}
  #section2 {padding-top:50px;height:500px;color: #fff;background-image: url("images/image2.jpg"); }
  #section3 {padding-top:50px;height:500px;color: #fff; background-image: url("images/image3.jpg");}
  #section41 {padding-top:50px;height:500px;color: #fff; background-image: url("images/image4.jpg");}
  #section42 {padding-top:50px;height:500px;color: #fff; background-image: url("images/image5.jpg");}
  
  
  .dropdown-menu>.active>a, .dropdown-menu>.active>a:focus, .dropdown-menu>.active>a:hover {
    background-color: #333 !important;
   
}
  
  </style>
</head>
<body data-spy="scroll" data-target=".navbar" data-offset="50">

<nav class="navbar navbar-inverse navbar-fixed-top">
  <div class="container-fluid">
    <div class="navbar-header">
        <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>                        
      </button>
      <a class="navbar-brand" href="http://dessdesign.com">DessDesign</a>
    </div><!-- close navbar header-->
    <div>
      <div class="collapse navbar-collapse" id="myNavbar">
        <ul class="nav navbar-nav">
          <li><a href="#section1">Section 1</a></li>
          <li><a href="#section2">Section 2</a></li>
          <li><a href="#section3">Section 3</a></li>
          <li class="dropdown"><a class="dropdown-toggle" data-toggle="dropdown" href="#">Section 4 <span class="caret"></span></a>
            <ul class="dropdown-menu">
              <li><a href="#section41">Section 4-1</a></li>
              <li><a href="#section42">Section 4-2</a></li>
            </ul>
          </li>
        </ul>
      </div>
    </div>
  </div>
</nav>    

<div id="section1" class="container-fluid">
  <h1>Section 1</h1>
  <p>Your content here</p>
</div>
<div id="section2" class="container-fluid">
  <h1>Section 2</h1>
  <p>Your content here</p>
</div>
<div id="section3" class="container-fluid">
  <h1>Section 3</h1>
  <p>Your content here</p>
</div>
<div id="section41" class="container-fluid">
  <h1>Section 4 Submenu 1</h1>
  <p>Your content here</p>
</div>
<div id="section42" class="container-fluid">
  <h1>Section 4 Submenu 2</h1>
 <p>Your content here</p>
</div>

</body>
</html>
