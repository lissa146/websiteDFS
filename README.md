# websiteDFS
<!DOCTYPE html>
<html lang="en">
<head>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Lato", sans-serif}
.w3-bar,h1,button {font-family: "Montserrat", sans-serif} {font-size:200px}
</style>
</head>
<body>

<!-- Navbar -->
<div class="w3-top">
  <div class="w3-bar w3-container w3-teal w3-card w3-left-align w3-large">
    <a class="w3-bar-item w3-button w3-hide-medium w3-hide-large w3-right w3-padding-large w3-hover-white w3-large w3-red" href="javascript:void(0);" onclick="myFunction()" title="Toggle Navigation Menu"><i class="fa fa-bars"></i></a>
    <a href="#" class="w3-bar-item w3-button w3-padding-large w3-white">Home</a>
    <a href="#" class="w3-bar-item w3-button w3-hide-small w3-padding-large w3-hover-white">boards</a>
    <a href="#" class="w3-bar-item w3-button w3-hide-small w3-padding-large w3-hover-white">303 boards</a>
    <a href="#" class="w3-bar-item w3-button w3-hide-small w3-padding-large w3-hover-white">donate</a>
    <a href="#" class="w3-bar-item w3-button w3-hide-small w3-padding-large w3-hover-white">pictures</a>
  </div>

  <!-- Navbar on small screens -->
  <div id="navDemo" class="w3-bar-block w3-white w3-hide w3-hide-large w3-hide-medium w3-large">
    <a href="#" class="w3-bar-item w3-button w3-padding-large">Link 1</a>
    <a href="#" class="w3-bar-item w3-button w3-padding-large">Link 2</a>
    <a href="#" class="w3-bar-item w3-button w3-padding-large">Link 3</a>
    <a href="#" class="w3-bar-item w3-button w3-padding-large">Link 4</a>
  </div>
</div>

<!-- Header -->
<header class="w3-container w3-cyan w3-center" style="padding:128px 16px">
  <h1 class="w3-margin w3-jumbo">Dumpster fire skate company</h1>
  <p class="w3-xlarge">a skate companying trying to support the skate community</p>
  <button class="w3-button w3-black w3-padding-large w3-large w3-margin-top">get started and start skating today</button>
</header>

<!-- First Grid -->
<div class="w3-row-padding w3-padding-64 w3-container">
  <div class="w3-content">
    <div class="w3-twothird">
      <h1>how we support our community</h1>
      <h5 class="w3-padding-32">also start skating today. skateboarding is a get outlet for somepeople to get stuff out and be free for a bit. The DFS(dumpster Fire skate Company) likes to support the skate communiy espally teh less fortureate skaters among te community we donate to small skate stores also so they can provide people with there eqitment.</h5>

      <p class="w3-text-black"> one of our loyal skaters killing it out there.</p>
    </div>
    <img src="redbull.avif" alt="redbull" width="300"height="300">
    <img src="SB.jpg" alt="SB" width="300" height="300"> 
    <div class="w3-third w3-right">
      
    </div>
  </div>
</div>

<!-- Second Grid -->
<div class="w3-row-padding w3-light-blue w3-padding-64 
r">
  <div class="w3-content">
    <div class="w3-third w3-center">
      <img src="DFS.png" alt="DFS" width="300" height="300">
    </div>

    <div class="w3-twothird">
      <h1>our logo and how we started</h1>
      <h5 class="w3-padding-32">DFS started from as a small charity only geting a few hundrd here and there but once 303 boards helped us lanch our ideas we started geting more money to help other skaters.DFS became a popular charity for the skate community and how we are trying to help skaters be able to join compinions or get new equitment if they need it.</h5>

      <p class="w3-text-blue">DFS(dumpstater fire skate company)</p>
    </div>
  </div>
</div>

<div class="w3-container w3-black w3-center w3-opacity w3-padding-64">
    <h1 class="w3-margin w3-xlarge">Quote of the day: skate or die</h1>
<p> Also if you want to donate to our cause of helping skaters in need you can call us at, but in case you don't have a phone you can email us at.
(720)835-9471 DFScompany@gmail.com</p>
</div>

<!-- Footer -->
<footer class="w3-container w3-padding-64 w3-center w3-opacity">  
  <div class="w3-xlarge w3-padding-32">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-snapchat w3-hover-opacity"></i>
    <i class="fa fa-pinterest-p w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
 </div>
 <p>Powered by <a href="https://www.303boards.com/" target="_blank">303.boards</a></p>
</footer>

<script>
// Used to toggle the menu on small screens when clicking on the menu button
function myFunction() {
  var x = document.getElementById("navDemo");
  if (x.className.indexOf("w3-show") == -1) {
    x.className += " w3-show";
  } else { 
    x.className = x.className.replace(" w3-show", "");
  }
}
</script>

</body>
</html>
