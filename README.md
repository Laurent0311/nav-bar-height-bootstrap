# nav-bar-height-bootstrap
I cannot adjust the height of my navbar






<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

</head>

<body>
    


<style>
body, html {
  height: 100%;
  margin: 0;

}
  
/*
.navbar-collapse {   background-color :#EBDCC1;
} */
   
/*
.navbar-brand { 
  background-color :#EBDCC1;
}  */


    

/* This class is already present in Bootstrap navbar. No need to add maually *
.navbar-toggler {*/
   
	
* {
  box-sizing: border-box;
}

.bg-image {
  /* Full height */
  height: 50%; 
  opacity: 0.65;
  /* Center and scale the image nicely */
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

/* Images used */
.img1 { background-image: url("https://media.istockphoto.com/photos/funny-group-of-dogs-at-the-hairdressers-or-groomer-picture-id538165049?k=6&m=538165049&s=612x612&w=0&h=WJxP1JGgZbtjIMc3Rhh_UGCKVqLXXBA-IOvWSeA6y5I="); }
.img2 { background-image: url("https://media.istockphoto.com/photos/yorkshire-terrier-is-being-brushed-by-groomer-picture-id495016554?k=6&m=495016554&s=612x612&w=0&h=IG6Gj9J0IohJNBpQhJ3E_Xa4MUrbSvVNYijxUrB9JVE="); }
.img3 { background-image: url("https://media.istockphoto.com/photos/cavalier-king-charles-spaniel-dog-grooming-session-picture-id969097426?k=6&m=969097426&s=612x612&w=0&h=9bcejS4bWtxu3zPpiXSa2QKm51hJZr3Wj45u85GmYs4="); }
.img4 { background-image: url("https://media.istockphoto.com/photos/young-cute-happy-little-white-dog-is-having-his-fur-on-paws-trimmed-picture-id944942222?k=6&m=944942222&s=612x612&w=0&h=VQBv3FjBcJl43277nipvpd3LC3a6ZhdBGaFv_WFajH0="); }
.img5 { background-image: url("https://media.istockphoto.com/photos/yorkie-dog-and-teddy-bear-friend-at-the-beauty-salon-picture-id505524522?k=6&m=505524522&s=612x612&w=0&h=40PebI5kG1nRIbBSEp4oRvJ-v84E-Rb0LxMrEFVarkM="); }
.img6 { background-image: url("https://media.istockphoto.com/photos/pet-groomer-with-scissors-makes-grooming-dog-picture-id1065436826?k=6&m=1065436826&s=612x612&w=0&h=2ASzFmXzz_AFt7Wq9LP_xetxLoLJj0vPgDwR7_iY9SQ="); }

/* banniere */
.bg-text {
  
  background-color:#EBDCC1; / Fallbac color
  background-color: rgba(0,0,0, 0.4); /* Black w/opacity/see-through */
  color: withe ;
  font-size: 14px;
  position: fixed;
  top: 80%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: 2;
  width: 350px;
  height: 160px;
  padding: 2px;
  text-align: center;
  font-family: 'proxima-nova';
}

.caption {
   position: absolute;
   left: 0;
   top: 50%;
   width: 100%;
   text-align: center;
   color: #EBDCC1;
}
        
.caption span.border {
    background-color: #111;
    color: #fff;
    padding: 18px;
    font-size: 25px;
    letter-spacing: 10px;
}


IMG.displayed {
 
 background-color: #EBDCC1 (0,0,, 0.4); /* Black w/opacity/see-through */

 position: fixed;
 top: 30%;
 left: 80%;
 transform: translate(-50%, -50%);
 width: 600px;
 height: 160px;
 padding: 20px;
 display: block;
 margin-left: auto;
 margin-right: auto 

}

/* logo  */

IMG.displayed {

 scroll-margin-left: 50px; 
 padding: 16px;  
 font-size: 20px;
 width: 400px;
 height: 400px;
 text-align: center;
 text-decoration: none;
 border-radius: 50%;
 
}

body {
  margin: 0;
  font-family:'proxima-nova'; bold;
}


.logo_superpose img {
  position:absolute;
}


header {
  background-color: #EBDCC1;

}





/* navbar  */

/* This class is already present in Bootstrap navbar. No need to add maually */
.navbar-toggler {
    background: rgba(235, 220, 193, 1) !important;  /* Give transparent white background to navbar */
                                                   /* 0.2 to give little whitish effect. */
                                                   /* Put 0 to get complete transperency */
    z-index: 2;
    backdrop-filter: blur(10px) saturate(125%);                   /* Blur the background */
                                                                  /* 10px Gaussian Blur and saturate for fluent design */
    -webkit-backdrop-filter: blur(10px) saturate(125%);          /* Increases browser compability (safari ios and mac) */
}
  
/*
.navbar-toggler {
  margin-top: 15px;
  ;
  */
}

@media screen and (min-width: 992px) {
  .navbar {
      min-height: 50px;
     







      
   }

  #logo {
    width: 260px;
    height: 120px;
    position: relative;
    
   
  }
  
.navbar  {
   min-height: 5rem;
   max-height:5rem;
    height:5rem;
    
  }
#nav-left {
    padding-left: 30px;
    
  
}




/* reseau sociau */


.fa {
  padding: 10px;
  font-size: 20px;
  width: 30px;
  text-align: center;
  text-decoration: none;
  margin: 2px 1px;
  border-radius: 50%;
}

.fa:hover {
    opacity: 0.7;
}

.fa-facebook {
  background: #EBDCC1;
  color: white;
}

.fa-instagram {
  background: #EBDCC1;
  color: white;
}

.content img
{

margin: 3px;
width: 300px;
height:300px;
float:right; 
}

</style>




<header>

   
    ​<nav class="navbar navbar-toggleable-md navbar-light bg-faded">
    <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarMobile" aria-controls="navbarMobile" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
    </button>
        
<div class="collapse navbar-collapse" id="nav-left">
    <ul class="nav navbar-nav">
        <li class="nav-item">
         <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item">
         <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item">
         <a class="nav-link" href="#">Link</a>
        </li>
    </ul>
</div>
        
<img src="image00.png" width="250rem" height="250rem " a class="navbar-brand mx-auto" href="#"><div id="logo"></div></img>
        
<div class="collapse navbar-collapse">
    <ul class="nav navbar-nav ml-auto">
        <li class="nav-item">
         <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item">
         <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item">
         <a class="nav-link" href="#">Link</a>
        </li>
    </ul>
</div>
      
       
<div class="collapse" id="navbarMobile">
    <ul class="nav navbar-nav">
        <li class="nav-item">
         <a class="nav-link" href="nosartisans.html">Partenaires</a>
        </li>
        <li class="nav-item">
         <a class="nav-link" href="paralax1.html">Services</a>
        </li>
        <li class="nav-item">
         <a class="nav-link" href="grilletarifairejustine.html">Tarifs</a>
        </li>
              
    </ul>
</div>
    </nav>

</header>

    <div class="slider">
    </div> 
    <div class="bg-image img1"></div>
    <div class="bg-image img2"></div>
    <div class="bg-image img3"></div>
    <div class="bg-image img4"></div>
    <div class="bg-image img5"></div>
    <div class="bg-image img6"></div>



    <div class="bg-text">
  <a href="#" class="fa fa-facebook"></a>
  <a href="https://instagram.com/rosy_englishcockerspaniel?igshid=9g0sk8jg6n9w" class="fa fa-instagram"></a>
     <p>Place de l'eglise
      1110 Morges</p>
     <p>+41784164046</p>
     <p>info@flairandco.ch</p>
    </div>

</body>

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css" integrity="sha384-TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2" crossorigin="anonymous">

<!-- jQuery and JS bundle w/ Popper.js -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx" crossorigin="anonymous"></script>
    
    
</html>


