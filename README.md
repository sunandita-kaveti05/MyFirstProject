# MyFirstProject
This is my first project.I developed Amazon clone using HTML, CSS

<html>
<head>
<style>
*{
  margin:0;
  font-family:Arial;
  border:border-box;
}
.navbar{
  height:60px;
  background-color:black;
  color:white;
  display:flex;
  align-items:center;
  justify-content:space-evenly;
}
.nav-logo{
  height:50px;
  width:100px;
}

 .logo{
  background-image:url("amazon_logo.png");
  background-size:cover;
  height:50px;
  width:100px;    
}
.border{
  border:1px solid transparent;
}
.border:hover{
  border:1px solid white;
}
.a1{
  color:#cccccc;
  font-size:0.8 rem;
  margin-left:15px;
}
.a2{
  margin-left:3px;   

}
.adicon{
  display:flex;
  align-iems:center;

}
.nav-search{
   display:flex;
   justify-content:space-evenly;
   width:620px;
   height:40px;
   border-radius:4px;

}
.s1{
  background-color:white;
  width:50px;
  text-align:center;
  border-top-left-radius:4px;
  border-bottom-left-radius:4px;
  border:none;
}
.s2{
  width:100%;
  font-size:1rem;
  border:none;
}
.sric{
  width:45px;
  display:flex;
  justify-content:center;
  align-items:center;
  font-size:1.2rem;
  background-color:orange; 
  border-top-right-radius:4px;
  border-bottom-right-radius:4px;
  color:black;
}
.nav-search:hover{
 border:3px solid orange;

}
span{
  font-size:0.7rem;


}
.nav2{
  font-size:0.86rem;
  font-weight:700;

}
.navcart i{
  font-size:30px; 
  font-weight:700; 

}

.panel{
  height:40px;
  background-color:#222f3d;
  display:flex;
  align-items:center;
  justify-content:space-evenly;
  color:white;
}
.panela{
  margin-left:0px;
}
.panel-options pre{
  display:inline;
  margin-left:10px;
}  
.options{
  width:70%;
  font-size:0.86rem;
}
.deal{
  font-size:0.9rem;
  font-weight:700;
  
} 
.con{
  background-image:url("dad.jpg");
  background-size:cover;
  height:400px;
  display:flex;
  align-items:flex-end;
  justify-content:center;
  
}
.msg{
  background-color:white;
  color:black;
  height:40px;
  display:flex;
  align-items:center;
  justify-content:center;
  font-size:0.85rem;
  width:80%;
  margin-bottom:25px;
}
.msg a{
  color:#007185
}
.shop{
  display:flex;
  flex-wrap:wrap;
  justify-content:space-evenly;
  background-color:#e2e7e6;
  

}
.box{
  height:400px;
  width:23%;
  background-color:white;
  padding:20px 0px 15px;
  margin:15px;


}
.bimg{
  height:300px;
  background-size:cover;
  margin-top:1rem;
  margin-bottom:1rem;
  

}
.boxcon{
  margin-left:1rem;
  margin-right:1rem;

}
.boxcon p{
  color:#007185;
  font-weight:400;
}
footer{
 margin-top:15px;

}
.f1{
  background-color:#374758;
  color:white;
  height:50px;
  display:flex;
  justify-content:center;
  align-items:center;
  font-size:0.5rem;
}
.f2{
   background-color:#222f3d;
   color:white;
   height:500px;
   display:flex;
   justify-content:space-evenly;
 }
ul{
  margin-top:20px;
}
ul a{
  display:block;
  font-size:0.86rem;
  margin-top:10px;
  color:#dddddd;

}
.f3{
  background-color:#222f3d;
  color:white;
  border-top:0.5px solid white;
  height:70px;
  display:flex;
  justify-content:center;
  align-items:center;
}
.lg{
  background-image:url("amazon_logo.png");
  background-size:cover;
  height:50px;
  width:100px;
}

.f4{
  background-color:black;
  color:white;
  height:80px;
  text-align:center;
}
.pages{
  font-size:0.7rem;
  padding-top:25px;

}
.copy{
  font-size:0.7rem;
  padding-top:5px;
}
.but{
   height:50px;
   width:80%;
   display:flex;
   justify-content:center;
   align-items:center;

}
.b{
   margin:10px;
   height:35px;
   width:200px;
   text-align:center;
   background-color:orange;
   color:black;
   font-wight:600;
  
}

</style>
</head>
<body>
  <header>
    <div class="navbar">
       <div class="nav-logo border">
           <div class="logo"></div>
       </div>
      <div class="navad border">
          <p class="a1">Deliver to</p>
          <div class="adicon">
              <i class="fa-solid fa-location-dot"></i>
              <p class="a2">India</p>
           </div>
      </div>
<div class="nav-search">
  <select class='s1'>
    <option>All</option>
  </select>
  <input  class='s2' placeholder="Search Amazon">
  <div class="sric"><i class="fa-solid fa-magnifying-glass"></i></div> 
</div>
<div clas="navsign border">
<p><span>Hello,sign in</span></p>
<p class="nav2">Account & Lists</p>
</div>
<div clas="navretn border">
<p><span>Returns</span></p>
<p class="nav2">& Orders</p>
</div>
<div class="navcart border">
  <i class="fa-solid fa-cart-shopping"></i>
  Cart
</div>
</div>

<div class="panel">
 <div class="panela">
   <i class="fa-solid fa-bars"></i>
   All
</div>
<div class="options">
  <pre>Today's Deals  Customer  Service  Registry  GiftCards  Sell</pre> 
</div>
<div class="deal">
Shop Deals In Elctronics
</div>
</div>
</header>
<div class="con">
   <div class="msg">
     <p>You are on amazon.com. You can also shop on Amazon India for millions of products with fast local delivery.<a> Click here to go to amazon.in </a></p>
   </div>
</div>


<div class="shop">
  <div class="box">
   <div class="boxcon">
    <h2>Health & Personal care</h2>
    <div class="bimg" style="background-image:url('box2_image.jpg')" ></div>
    <p>See more</p>
  </div>
  </div>
  <div class="box">
    <div class="boxcon">
    <h2>Study space</h2>
    <div class="bimg" style="background-image:url('box3_image.jpg')" ></div>
    <p>Shop Now</p>
  </div>
</div>
  <div class="box">
   <div class="boxcon">
    <h2>Electronics</h2>
    <div class="bimg" style="background-image:url('box4_image.jpg')" ></div>
    <p>See more</p>
  </div>
</div>
  <div class="box">
     <div class="boxcon">
    <h2>Beauty picks</h2>
    <div class="bimg" style="background-image:url('box5_image.jpg')" ></div>
    <p>See more</p>
  </div>
</div>
<div class="box">
   <div class="boxcon">
    <h2>Smartwatches</h2>
    <div class="bimg" style="background-image:url('box65_image.jpg')" ></div>
    <p>See more</p>
  </div>
  </div>
  <div class="box">
    <div class="boxcon">
    <h2>New arrivals in Toys</h2>
    <div class="bimg" style="background-image:url('box7_image.jpg')" ></div>
    <p>See more</p>
  </div>
</div>
  <div class="box">
   <div class="boxcon">
    <h2>Discover FASHION trends</h2>
    <div class="bimg" style="background-image:url('box8_image.jpg')" ></div>
    <p>See more</p>
  </div>
</div>
  <div class="box">
     <div class="boxcon">
    <h2>Refresh Your Space</h2>
    <div class="bimg" style="background-image:url('box9_image.jpg')" ></div>
    <p>Shop Kitchen Upgrades</p>
     </div>
 </div>
<div class="box">
     <div class="boxcon">
    <h2>For Your Fitness Needs</h2>
    <div class="bimg" style="background-image:url('box10_image.jpg')" ></div>
    <p>Shop Now</p>
     </div>
 </div>
</div>
<div class="but">
<p class="z">
For Personalised Recommendations</p>
<button class="b">Sign In</button>
</div>
<footer>
<div class="f1">Back To Top</div>
<div class="f2"><ul>
<p>Get To Know Us</p>
<a>carers</a>
<a>Blog</a>
<a>About Amazon</a>
<a>Investor Relations</a>
<a>Amazon Devices</a>
<a>Amazon Science</a>
</ul>
<ul>
<p>Make Money with Us</p>
<a>Sell products on Amazon</a>
<a>Sell on Amazon Business</a>
<a>Sell apps on Amazon</a>
<a>Become an Affiliate</a>
<a>Advertise Your Products</a>
<a>Self-Publish with Us</a>
<a>Host an Amazon Hub</a>
<a>›Se More Make Money with Us</a>
</ul>
<ul>
<p>Amazon Payment Products</p>
<a>Amazon Business Card</a>
<a>Shop with Points</a>
<a>Reload Your Balance</a>
<a>Amazon Currency Converter</a>
</ul>
<ul>
<p>Let Us Help You</p>
<a>Amazon and COVID-19</a>
<a>Your Account</a>
<a>Your Orders</a>
<a>Shipping Rates & Policies</a>
<a>Returns & Replacements</a>
<a>Manage Your Content and Devices</a>
<a>Amazon Assistant</a>
<a>Help</a>
</ul></div>
<div class="f3">
  <div class="lg"></div>
</div>
<div class="f4">
<div class="pages">
<a>Conditions of Use </a>
<a>Privacy Notice</a>
<a>Your Ads Privacy Choices </a>
</div>
<div class="copy">
   © 1996-2023, Amazon.com, Inc. or its affiliates
</div>
</div>
</footer>
</body>
</html>
