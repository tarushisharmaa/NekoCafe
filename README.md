<!DOCTYPE html>
<html>
    <head>
<title>chef page</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body {
  margin: 0;
  font-family: URW Chancery L, cursive;
  
}

.topnav {
    top: 0%;
  overflow: hidden;
  background-color:whitesmoke;
   opacity: 0.5;
  position:fixed ;
  z-index: 1000;
  width: 100%;
}

.topnav a {
  float: left;
  display: block;
  color: #000;
  text-align: center;
 
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color:whitesmoke;
  color: black;
}

.topnav a.active {
  background-color:whitesmoke;
  color:whitesmoke;
}
.icon{
    right: 2%;
}

.topnav .icon {
  display: none;
}

@media screen and (max-width: 600px) {
  .topnav a:not(:first-child) {display: none;}
  .topnav a.icon {
    float: right;
    display: block;
  }
}

@media screen and (max-width: 600px) {
  .topnav.responsive {position: relative;}
  .topnav.responsive .icon {
    position: absolute;
    right: 4;
    top: 5;
  }
  .topnav.responsive a {
    float: none;
    display: block;
    text-align: center;
  }
}
</style>
<style>
    body, html {
      height: 100%;
    }
    
    .parallax {
      /* The image used */
      background-image: url('https://cdn.squaremeal.co.uk/article/9282/images/catlantis-is-opening-in-marylebone_09082019093922.jpg?w=913&auto=format%2Ccompress');
      filter: brightness(80%);
      /* Full height */
      height: 100%; 
    width: 100%;
      /* Create the parallax scrolling effect */
      background-attachment: fixed;
      background-position: center;
      background-repeat: no-repeat;
      background-size: cover;
    }



    * {
          box-sizing:border-box;
          color: black;
        }
        
        .flex-container {
          display: flex;
          flex-direction: row;
          font-size: 15px;
          text-align: center;
        }
        
        .flex-item-left {
          background-color:white;
          
          flex: 30%;
        }
        
        .flex-item-right {
          background-color: white;
          
          flex: 30%;
        }
        
        /* Responsive layout - makes a one column-layout instead of two-column layout */
        @media (max-width: 800px) {
          .flex-container {
            flex-direction: column;
          }
        }

    </style>
    <style>
        .container {
          position: relative;
          text-align: center;
          color: white;
          font-family: URW Chancery L, cursive;
        }
    
        
        .centered {
          position: absolute;
          top: 50%;
          left: 50%;
          transform: translate(-50%, -50%);
        }
         .btn {
  position: absolute;
  top: 80%;
  left: 10%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  background-color: #f1f1f1;
  color: black;
  font-size: 16px;
  padding: 16px 30px;
  border: none;
  cursor: pointer;
  border-radius: 5px;
  text-align: center;
  min-width: fit-content;
  font-family: URW Chancery L, cursive;
}

 .btn:hover {
  background-color: black;
  color: white;
}
.btn2 {
  position: absolute;
  top: 80%;
  left: 90%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  background-color: #f1f1f1;
  color: black;
  font-size: 16px;
  padding: 16px 30px;
  border: none;
  cursor: pointer;
  border-radius: 5px;
  text-align: center;
  min-width: fit-content;
  font-family: URW Chancery L, cursive;
}

 .btn2:hover {
  background-color: black;
  color: white;
}

.btn3 {
  position: absolute;
  top: 50%;
  left: 90%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  background-color: #f1f1f1;
  color: black;
  font-size: 16px;
  padding: 16px 30px;
  border: none;
  cursor: pointer;
  border-radius: 5px;
  text-align: center;
  min-width: fit-content;
  font-family: URW Chancery L, cursive;
}

 .btn3:hover {
  background-color: black;
  color: white;
}
.fa {
  padding-left: 30px;
  padding-right: 30px;
  font-size: 30px;
  width: 30px;
  text-align: center;
  text-decoration: none;
  margin: 5px 2px;
  border-radius: 50%;
}

.fa:hover {
    opacity: 0.7;
}

.fa-facebook {
  
  color:sienna;
}

.fa-instagram {
  
  color:sienna;
}

.fa-youtube {

  color:sienna;
}
.fa-rss{
    color: sienna;
}
.fa-twitter{
    color: sienna;
}
.row{
        display: flex;
  flex-wrap: wrap;
}
        </style>
    </head>
    <body>

        <div class="topnav" id="myTopnav">
            <a href="#home" class="active" style="padding-left: 2%;width:10px;height:5px;"><img src=""></a>
            <a href="#news" style=" padding: 24px 40px;;">Home</a>
            <a href="#contact" style=" padding: 24px 40px;">About Us</a>
            <a href="#news" style=" padding: 24px 40px;">chef</a>
            <a href="#contact" style=" padding: 24px 40px;">Blog</a>
            <a href="#about" style=" padding: 24px 40px;">Contact Us</a>
            <a href="#reservation" ><div class="btn3">RESERVATION</div></a>
            <a href="javascript:void(0);" class="icon" onclick="myFunction()">
              <i class="fa fa-bars"></i>
            </a>
          </div>
          
        
<div class="parallax">
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>

    <h1 style="text-align: center;font-size: 400%;"><b style=" font-family: URW Chancery L, cursive;"><u>The Neko Cafe</u></b><br>
        Cat based cafe</h1>
</div>

<div style="height:fit-content;background-color:white;font-size:36px">
    <br>
<h1 style="font-size: 100%;text-align: center;"><b><u>HERE ARE OUR AWARD WINNING CHEFS</u></b></h1>
<br>
<div class="flex-container">
    <div class="flex-item-left" style="max-width:100%;">
        <image style="max-width:80%;" src="https://dinery.deothemes.com/wp-content/uploads/2020/06/07_restaurant_chief_1-min.jpg"></image>
        <br>
        <br>
        <b style="color:sienna;font-size: 230%;">JOHN BENNETT</b><br>LEAD CHEF<br><br>
        <a href="#" class="fa fa-facebook"></a>
        <a href="#" class="fa fa-instagram"></a>
        <a href="#" class="fa fa-youtube"></a>
        <a href="#" class="fa fa-twitter"></a>
        <br>
        <p style="padding-left: 20%;padding-right: 20%;">Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusa ntium doloremque. Aliquam et elit eu nunc rhoncus viverra</p>
        <br>
        <br>
     </div>
    <div class="flex-item-right" style="max-width:100%;">
        <image style="max-width:80%;" src="https://dinery.deothemes.com/wp-content/uploads/2020/06/07_restaurant_chief_2-min.jpg"></image>
        <br>
        <br>
        <b style="color:sienna;font-size: 230%;">JESSICA DOE</b><br>LEAD CHEF<br><br>
        <a href="#" class="fa fa-facebook"></a>
        <a href="#" class="fa fa-instagram"></a>
        <a href="#" class="fa fa-youtube"></a>
        <a href="#" class="fa fa-twitter"></a>
        <br>
        <p style="padding-left: 20%;padding-right: 20%;">Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusa ntium doloremque. Aliquam et elit eu nunc rhoncus viverra</p>
    </div>
    
   </div>
</div>
<br>
<br>
<div>
    <img style="width: 100%;max-height: 500px;filter: brightness(80%);" src="https://i.pinimg.com/736x/55/18/b5/5518b58e5299a28803d422f9d8abd958.jpg";>
</div>
<br>
<br>
<br>
<br>
<br>
<br>
<div class="flex-container">
    <div class="flex-item-left" style="max-width:100%;"><image style="max-width:80%;" src="https://dinery.deothemes.com/wp-content/uploads/2020/06/07_restaurant_chief_3-min.jpg"></image><br><br> <b style="color:sienna;font-size: 230%;">KRISTEN HARDY</b><br>JAPANESE CUISINE<br><br>
        <a href="#" class="fa fa-facebook"></a>
        <a href="#" class="fa fa-instagram"></a>
        <a href="#" class="fa fa-youtube"></a>
        <a href="#" class="fa fa-twitter"></a>
        <br>
        <p style="padding-left: 20%;padding-right: 20%;">Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusa ntium doloremque. Aliquam et elit eu nunc rhoncus viverra</p> </div>
    <div class="flex-item-right" style="max-width:100%;"><image style="max-width:80%;" src="https://dinery.deothemes.com/wp-content/uploads/2020/06/07_restaurant_chief_4-min.jpg"></image><br><br> <b style="color:sienna;font-size: 230%;">OLIVER JAMES</b><br>FRENCH KITCHEN LEAD<br><br>
        <a href="#" class="fa fa-facebook"></a>
        <a href="#" class="fa fa-instagram"></a>
        <a href="#" class="fa fa-youtube"></a>
        <a href="#" class="fa fa-twitter"></a>
        <br>
        <p style="padding-left: 20%;padding-right: 20%;">Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusa ntium doloremque. Aliquam et elit eu nunc rhoncus viverra</p> </div>
    <div class="flex-item-right" style="max-width:100%;"><image style="max-width:80%;" src="https://dinery.deothemes.com/wp-content/uploads/2020/06/07_restaurant_chief_5-min.jpg"></image><br><br> <b style="color:sienna;font-size: 230%;">OLIVER JAMES</b><br>PÂTISSIER<br><br>
        <a href="#" class="fa fa-facebook"></a>
        <a href="#" class="fa fa-instagram"></a>
        <a href="#" class="fa fa-youtube"></a>
        <a href="#" class="fa fa-twitter"></a>
        <br>
        <p style="padding-left: 20%;padding-right: 20%;">Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusa ntium doloremque. Aliquam et elit eu nunc rhoncus viverra</p> </div>
   </div>
<br>
<br>
<br>
<br>
<div class="container">
    <img src="https://qph.cf2.quoracdn.net/main-qimg-382517e511af2d7ce957fcfa0d955b1c-lq" alt="food" style="width: 100%;max-height: 600px;  filter: brightness(50%);">
   
    <div class="centered" style="color: whitesmoke;font-family:fantasy;font-size: 290%;height: fit-content;">
        <br>
       <b style="color: white;font-family: URW Chancery L, cursive;color: sienna;"> Reservation</b><br>
        YOU ORDER, WE DELIVER
        <br>
        <p style="color: whitesmoke;bottom: 0;font-size: 40%;"> CALL - 920.274.0366</p>
        <br>
        <br>
      
        <div class="flex-container" >
            <div class="flex-item-left" style="max-width:100%;">
                <button class="btn">SEE MENU <br>& ORDER</button>
            </div>
            <div class="flex-item-right" style="max-width:100%;">
                <button class="btn2">TABLE <br>RESERVATIONS</button>
            </div>
           </div>
         
        </div>
      
</div>

<div style="background-color:whitesmoke;height:fit-content">
    <br>
    <br>
    <br>
    <div class="row" >
        <div class="column2" style="text-align: center;padding-left: 8%;padding-right: 4%;">
           
         <p style="text-align: center;"><br>
            
        
            <i style="font-size:24px;color:sienna;" class="fa">&#xf041;</i>
            <br><b>ADDRESS</b><br><br>
            Algonquin college,<br>
             E building</p>
  </div>
  <div class="column2" style="text-align: center;padding-left: 7%;padding-right: 4%;">
           
    <p style="text-align: center;"><br>
       
   
       <i style="font-size:24px;color:sienna;" class="fa">&#xf017;</i>
       <br><b> WE ARE OPEN</b><br><br>
      <b> Mon–Fri:</b> 9am-10pm<br>
       <b>Sat:</b> 10pm-4am<br>
       <b>Sun:</b> 10am-7pm</p>
</div>
<div class="column2" style="text-align: center;padding-left: 6%;padding-right: 3%;">
           
    <p style="text-align: center;"><br>
       
       <i style="font-size:24px;color:sienna;" class="fa">&#xf095;</i>
       <br><b> RESERVATION</b><br><br>
       +91 9206738476<br>
       catcafe@dinery.com</p>
</div>
<div class="column2" style="text-align: center;padding-left: 3%;padding-right: 1%;">
    <p style="text-align: center;">
        <br>
        <i style="font-size:24px;color:sienna;" class="fa">&#xf08a;</i>
        <br><b> STAY CONNECTED</b><br></p>
            <a href="#" class="fa fa-facebook"></a>
            <a href="#" class="fa fa-instagram"></a>
            <a href="#" class="fa fa-youtube"></a>
            <a href="#" class="fa fa-rss"></a>
</div>
</div>
<br>
<br>
<br>
<br>
</div>
<br>
<br>
<br>
<div class="flex-container" style="font-size: 77%;">
   
    <div class="flex-item-left" style="max-width:100%;">
        <p style="color: silver;">Privacy Policy Terms & Conditions</p>
    </div>
    <div class="flex-item-right" style="max-width:100%;">
        <p style="color: silver;">© 2021 Dinery, Made by DeoThemes</p>
    </div>
   </div>
   <br>
   <br>
   <br>
          <script>
          function myFunction() {
            var x = document.getElementById("myTopnav");
            if (x.className === "topnav") {
              x.className += " responsive";
            } else {
              x.className = "topnav";
            }
          }
          </script>
          
    </body>
</html>
