<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="icon" type="image/jpg" href="pics/favicon.jpg">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CROCHET</title>
    <link rel="stylesheet" href="css/header.css">
    <link rel="stylesheet" href="css/body.css">
    <link rel="stylesheet" href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css">
    <link rel="stylesheet" href="css/login.css">
<!--swiper css
    <link rel="stylesheet" href="css/swiper-bundle.min.css">
-->
</head>
<body style="background-color: rgb(245, 201, 208);">
<header id="fix">
    <div class="logo">
        <img src="pics/logo.jpg" id="logo" alt="logo" align="left">
    </div>
    
    <br>
 <div id="dangnhap">
    <button onclick="document.getElementById('id01').style.display='block'" style="width:auto;" id="login">SIGN IN</button>    
    <button id="login"><a href="register.html">REGISTER</a></button>
<div id="id01" class="modal">  
  <form class="modal-content animate" action="/action_page.php" method="post">
    <div class="imgcontainer">
        <span onclick="document.getElementById('id01').style.display='none'" class="close" title="Close Modal">&times;</span>
        <img src="pics/login.jpg" alt="Avatar" class="avatar">
      </div>

    <div class="container">
        <h2>LOGIN FORM</h2>
      <label for="uname"><b>Username</b></label>
      <i class='bx bxs-user' ></i>
      <input type="text" placeholder="Username" required>
      

      <label for="psw"><b>Password</b></label>
      <i class='bx bxs-lock-alt'></i>
      <input type="password" placeholder="Password" required>
        
      <label>
        <input type="checkbox" checked="checked" name="remember"> Remember me
      </label>
      <br>
      <button type="submit" class="dn">Login</button>
    </div>

    <div class="container" style="background-color:#f1f1f1">
      <button type="button" onclick="document.getElementById('id01').style.display='none'" class="cancelbtn">Cancel</button>
      <span class="psw">Forgot <a href="#">password?</a></span>
      <span class="psw">Don't have an account?<a href="register.html">Register</a></span>
    </div>
  </form>
</div>

<!--   <button id="dangnhap">
        <a  href="register.html">REGISTER</a>
    </button>
    --> 
 </div>

<br>
<div class="search-box">
    <div class="input-box">            
        <input type="search" id="search" placeholder="Tìm kiếm...">
        <a href="#" class="search-btn">
            <i class='bx bx-search-alt-2'></i>
        </a>
    </div>
</div>
    <br>
    <div id="navfix">
        <ul class="navbar">    
            <li><a href="index.html"><b>MENU</b></a></li>
            <li><a href="intro.html"><b>ABOUT</b></a></li>
            <div class="dropdown">
                <li><a href="product.html"><b>PRODUCT</b></a></li>
                <div class="content">
                    <a href="">Flower</a>
                    <a href="">Stuffed animal</a>
                    <a href="">Key chain</a>
                    <a href="">Clothes</a>
                    <a href="">Tote</a>
                    <a href="">...</a>
                </div>
            </div>
           
            <div class="dropdown">
                <li><a href="learn.html"><b>LEARN</b></a></li>
                <div class="content">
                    <a href="">Basic chart</a>
                    <a href="">Another chart</a>
                </div>
            </div>
            <li><a href="shop.html"><b>SHOP</b></a></li>
            <li><a href="contact.html"><b>CONTACT</b></a></li>
           
        </ul>
    </div>
    
</header>

    <img src="pics/slide1.png" alt="gt" class="anhgt1">

    <table class="khunggt">
        <tr>
        <th class="slide"><div id="chuoigt1">
            <div class="share">
                <h2><a href="learn.html">Share for free</a></h2>
                <p>Share useful knitting knowledge and interesting crochet tips</p>
            </div>
        </div></th>
        <th><div id="chuoigt2">
            <div class="buy">
                <h2><a href="">Shopping</a></h2>
                <p>All kinds of cheap and quality knitting accessories, reputable handmade gifts</p>
            </div>
        </div></th>
        </tr>
    </table>
    <br>
    <table>
        <tr>
            <th class="vid">
                <video width="400px" height="400px" controls autoplay>
            <source src="pics/vid.mp4">
        </video>
    </th>
        <th id="content">
            <h3>WHAT IS CROCHET?</h3>
            <p>Crochet is a type of needlecraft in which you use a hook to create fabric from loops of yarn. Crochet can be used to make everything from blankets and scarves to hats and sweaters. If you’re looking for a fun, creative way to spend your free time, crochet may be the perfect activity for you!</p>
            <hr width="30%" color="pink">
            <br>
            <h3>CROCHET HANDMADE</h3>
            <p>
                This is a website specializing in sharing easy-to-understand handmade instructions, especially wool and yarn handmade.
                At the same time, this is a place that provides reputable, quality, good-priced woolen yarn, crocheted accessories and handmade gifts to meet everyone's needs.
            </p>
        </th>
        </tr>
    </table>

    <div class="chuoi">
        <h1>SOME PRODUCTS</h1>
        <div id="slidesp">
            <div class="mang">
                <div class="chuoisp1">
                    <a>
                        <img class="image" src="pics/animal1.jpg">
                    </a>
                </div>
                <div class="infor">
                    <h4>Chick Amigurumi</h4>                        
                    <p>Cute wool chicken stew keychain...</p>
                    <button class="button"><a href="">Detail</a></button>  
                </div>  
            </div>
    
            <div class="mang">
                <div class="chuoisp1">
                    <a>
                        <img class="image" src="pics/flo1.jpg">
                    </a>
                </div>
                <div class="infor">
                    <h4>A Basket Of Flowers</h4>                        
                    <p>Mini flower basket made of wool...</p>
                    <button class="button"><a href="">Detail</a></button>  
                </div>  
            </div>
    
            <div class="mang">
                <div class="chuoisp1">
                    <a>
                        <img class="image" src="pics/animal2.jpg">
                    </a>
                </div>
                <div class="infor">
                    <h4>Rabit Keychain</h4>                        
                    <p>fdhgfythhgbdhfuehufjhueufffffffsd...</p>
                    <button class="button"><a href="">Detail</a></button>  
                </div>  
            </div>
    
            <div class="mang">
                <div class="chuoisp1">
                    <a>
                        <img class="image" src="pics/tote1.jpg">
                    </a>
                </div>
                <div class="infor">
                    <h4>Flower Tote Bag</h4>                        
                    <p>fdhgfythhgbdhfuehufjhueufffffffsd...</p>
                    <button class="button"><a href="">Detail</a></button>  
                </div>  
            </div>
    
            <div class="mang">
                <div class="chuoisp1">
                    <a>
                        <img class="image" src="pics/clo1.jpg">
                    </a>
                </div>
                <div class="infor">
                    <h4>Sweet Woman Crop Top</h4>                        
                    <p>fdhgfythhgbdhfuehufjhueufffffffsd...</p>
                    <button class="button"><a href="">Detail</a></button>  
                </div>  
            </div>
    
            <div class="mang">
                <div class="chuoisp1">
                    <a>
                        <img class="image" src="pics/key1.jpg">
                    </a>
                </div>
                <div class="infor">
                    <h4>Car Pandent</h4>                        
                    <p>fdhgfythhgbdhfuehufjhueufffffffsd...</p>
                    <button class="button"><a href="">Detail</a></button>  
                </div>  
            </div>
    
            <div class="mang">
                <div class="chuoisp1">
                    <a>
                        <img class="image" src="pics/flo2.jpg">
                    </a>
                </div>
                <div class="infor">
                    <h4>A Basket Of Flowers</h4>                        
                    <p>Mini flower basket made of wool...</p>
                    <button class="button"><a href="">Detail</a></button>  
                </div>  
            </div>
    
            <div class="mang">
                <div class="chuoisp1">
                    <a>
                        <img class="image" src="pics/ano1.jpg">
                    </a>
                </div>
                <div class="infor">
                    <h4>Headbands</h4>                        
                    <p>fdhgfythhgbdhfuehufjhueufffffffsd...</p>
                    <button class="button"><a href="">Detail</a></button>  
                </div>  
            </div>
    
            <div class="mang">
                <div class="chuoisp1">
                    <a>
                        <img class="image" src="pics/key2.jpg">
                    </a>
                </div>
                <div class="infor">
                    <h4>Christmas Decorate</h4>                        
                    <p>The most adorable crochet Christmas Tree...</p>
                    <button class="button"><a href="">Detail</a></button>  
                </div>  
            </div>
    
            <div class="mang">
                <div class="chuoisp1">
                    <a>
                        <img class="image" src="pics/ano2.jpg">
                    </a>
                </div>
                <div class="infor">
                    <h4>Boombox Bag</h4>                        
                    <p>If you love retro like we do,...</p>
                    <button class="button"><a href="">Detail</a></button>  
                </div>  
            </div>

            <div class="mang">
                <div class="chuoisp1">
                    <a>
                        <img class="image" src="pics/flo5.jpg">
                    </a>
                </div>
                <div class="infor">
                    <h4>Tulip</h4>                        
                    <p>...</p>
                    <button class="button"><a href="">Detail</a></button>  
                </div>  
            </div>
    
            <div class="mang">
                <div class="chuoisp1">
                    <a>
                        <img class="image" src="pics/tote4.jpg">
                    </a>
                </div>
                <div class="infor">
                    <h4>Floral Square Shoulder Bag</h4>                        
                    <p>This mini cable bag free...</p>
                    <button class="button"><a href="">Detail</a></button>  
                </div>  
            </div>
    
            <div class="mang">
                <div class="chuoisp1">
                    <a>
                        <img class="image" src="pics/animal3.jpg">
                    </a>
                </div>
                <div class="infor">
                    <h4>Chinchilla Doll</h4>
                    <p>...</p>
                    <button class="button"><a href="">Detail</a></button>  
                </div>  
            </div>

            <div class="more">
                <button id="buttonmore">
                    <a href="product.html"><i class='bx bx-dots-horizontal-rounded'></i></a>                    
                </button>
            </div>
        </div>
    </div>

    <br>
    <hr>
    <footer style="background-color: rgb(124, 116, 124);" align="center">
        by: NgocTram<br>
        &copy; copyright reserved<br>
        <a href="mailto: truongtram2k4@gmail.com"><i class='bx bxl-gmail'></i>Mail</a>
    </footer>

</body>

</html>
