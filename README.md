# FinalProjectWebsite


Sources 

Template for Website
https://www.free-css.com/free-css-templates/page289/seotech

Singular Icon
https://www.flaticon.com/search?type=icon&word=computer+logo

URL for the Non copyrighted Avatars used for Icons.
<a href="https://www.freepik.com/free-vector/multiracial-people-avatars_7085153.htm#query=avatar&position=0&from_view=keyword&track=sph">Image by pikisuperstar</a> on Freepik

Icons for the website.
https://fontawesome.com/

Non-copyrighted images websites for the website.
https://www.pexels.com/

https://pixabay.com/



HTML CODE CHANGES

There are about 24 image additions or changes to his website. 
Theres 6 icon changes with the website. 

Changes between the About and Service HTML files are the same as the Index.html files. 
The about and service files are used for that you can tab to different sections of the website. 

The addition of the <img></img> command in the <span></span> section of the website. (Was added to show the logo of the website.) 

<span>
  Rogers Electronics
  <img src="images/logo1.jpg" alt="" height="40" width="50">
</span>

The entire Hero_Area div and slider_section class was changed. The background image was changed in that section. There were changes to the text and images used in that class. 

EX: From the Slider Section
<section class=" slider_section ">
 <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
   <div class="carousel-inner">
     <div class="carousel-item active">
       <div class="container">
         <div class="row">
           <div class="col-md-6 ">
             <div class="detail_box">
               <h1>
                 Express Shipping
               </h1>
               <p>
                 With express shipping, you'll get your products faster than ever before.
                 Say goodbye to waiting weeks for your order to arrive and hello to speedy delivery!
               </p>
               <div class="btn-box">
                 <a href="" class="btn-1">
                   Contact Us
                 </a>

EX: From the Hero_Area
<div class="hero_area">
 <!-- header section strats -->
 <header class="header_section">
   <div class="container-fluid">
     <nav class="navbar navbar-expand-lg custom_nav-container ">
       <a class="navbar-brand" href="index.html">
           <span>
              Rogers Electronics
              <img src="images/logo1.jpg" alt="" height="40" width="50">
           </span>
       </a>
       </a>
       <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
         <span class="s-1"> </span>
         <span class="s-2"> </span>
         <span class="s-3"> </span>
       </button>


The Service section was changed to the Products section of the website.

EX: Here it is
<section class="service_section layout_padding">
 <div class="container-fluid">
   <div class="heading_container">
     <h2>
       Our Products
     </h2>
     <p>
       Here are the products you can choose to buy.
     </p>
   </div>

EX: The icons that show up have changed. All of the images have changed and the text also changed. 
<div class="service_container">
 <div class="box">
   <div class="img-box">
     <img src="images/s-8.png" alt="">
   </div>
   <div class="detail-box">
     <h5>
       Tablets
     </h5>
     <p>
       We sell tablets from multiple brands such as Apple, Samsung, Google, Microsoft, Amazon, etc,
     </p>
   </div>
 </div>



The work section was changed into the FAQ section where common questions about the product or business are answered. 

EX: The work_section code that was changed to the FAQ section.
<section class="work_section layout_padding">
 <div class="container">
   <div class="heading_container">
     <h2>
       FAQ
     </h2>
     <p>
        Down bellow are common questions asked about our products and business.
     </p>
   </div>
   <div class="row">
     <div class="col-md-6">
       <div class="detail_container">
         <div class="box b-1">
           <div class="top-box">
             <div class="icon-box">
               <img src="images/discount.webp"  alt="">
             </div>
             <h5>
               How we get our products.
             </h5>


EX: Here is one of the bottom boxes added.  The text was changed and images were added. 
<div class="bottom-box">
 <p>
   We buy used  phones in bulk and sell them at a reasonable price to you. People also have the option to sell their
   used electronics to us.They also have the option to sell the electronic at a lower price which will give them a site wide discount on this website.
 <p></p>
 The phones are stored in a warehouse where we ship them to you within 2-4 bussiness days.
 <img src="images/storage.jpeg" alt="" width="400" height="200" >
 <p></p>
 We also make sure that any phone that we well is referbished. We clean them ourselfs.
 <img src="images/referbp.jpg" alt="" width="400" height="200" >


 </p>
</div>


The team section was changed to introduce the CEO, COO, and Storage Manager 

EX: The text and images were changed.
<div class="team_container">
 <div class="box b-1">
   <div class="img-box">
     <img src="images/c1.png" alt="">
   </div>
   <div class="detail-box">
     <h5>
       Haley Williams
     </h5>
     <p>
       As Roger Electronics COO,
       I'm focused on streamlining operations, improving efficiency, and ensuring that our customers are satisfied with their purchases.
     </p>


The Clients section was changed into the Review section 
<section class="client_section layout_padding-bottom">
 <div class="container">
   <div class="heading_container">
     <h2>
       Reviews from  Customers.
     </h2>
     <p>
       See what our happy customers have to say about our products and service.
     </p>
   </div>
 </div>



EX. The images and text changed. 
<div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
 <div class="carousel-inner">
   <div class="carousel-item active">
     <div class="container">
       <div class="box">
         <div class="img-box">
           <img src="images/pf2.png" alt=""  height="70" width="70"  >
         </div>
         <div class="detail-box">
           <h6>
             Peter Parker
           </h6>
           <p>
             I recently purchased a refurbished laptop from this company for college, and I'm thrilled with my purchase.
             The laptop is in excellent condition and works perfectly. It's been a great investment that has saved me a lot of money, and I would definitely recommend this company to anyone in need of a refurbished device.


           </p>


The Contact Us Section of the Website was changed to the Register section for people to “Register to log into the website”

The Password, Re-Type Password, and Message Sections were added.
<!-- contact section -->
<section class="contact_section layout_padding" id="contactLink">
 <div class="container">
   <div class="heading_container">
     <h2>
       Register
     </h2>
   </div>
 </div>
 <div class="container">
   <div class="row">
     <div class="col-lg-6 col-md-8 mx-auto">
       <form>
         <div class="form-row">
           <div class="form-group col-md-6">
             <input type="text" class="form-control" id="inputName4" placeholder="Name ">
           </div>
           <div class="form-group col-md-6">
             <input type="email" class="form-control" id="inputEmail4" placeholder="Email id">
           </div>


         </div>
         <div class="form-row">
           <div class="form-group col">
             <input type="text" class="form-control" id="inputPassword" placeholder="Password">
           </div>
         </div>
         <div class="form-group">
           <input type="text" class="form-control" id="inputRpassword" placeholder="Re enter password">
         </div>
         <div class="form-group">
           <input type="text" class="form-control" id="inputMessage" placeholder="Type down a message">
         </div>
         <div class="d-flex justify-content-center">
           <button type="submit" class="">Enter</button>
         </div>
       </form>
     </div>
   </div>
 </div>
</section>


The social_box icons were changed to use font awesome icons. 
EX:
<div class="social_box">
 <a href="">
   <i class="fa-brands fa-facebook-f" style="color: #ffffff;"></i>
 </a>
 <a href="">
   <i class="fa-brands fa-twitter" style="color: #ffffff;"></i>
 </a>
 <a href="">
   <i class="fa-brands fa-linkedin-in" style="color: #ffffff;"></i>
 </a>
 <a href="">
   <i class="fa-brands fa-youtube" style="color: #ffffff;"></i>
 </a>


The info section text was changed. Images and Icons were added. 
<section class="info_section layout_padding2">
 <div class="container">
   <div class="row">
     <div class="col-md-3">
       <div class="info_logo">
         <h3>
           Rogers Electronics
         </h3>
         <p>
           "Upgrade your tech, not your budget!
         <p></p>
         <img src="images/logo1.jpg" alt="" height="70" width="70">
         </p>
       </div>
     </div>
     <div class="col-md-3">
       <div class="info_links">
         <h4>
           BASIC LINKS
         </h4>
         <ul class="  ">
           <li class=" active">
             <a class="" href="index.html">Home <span class="sr-only">(current)</span></a>
           </li>
           <li class="">
             <a class="" href="about.html"> About</a>
           </li>
           <li class="">
             <a class="" href="service.html"> Services </a>
           </li>
           <li class="">
             <a class="" href="#contactLink">Register</a>
           </li>
         </ul>
       </div>

Images where added to the FQA question to add space in the area. 
<div class="col-md-6">
 <div class="img-box">
   <img src="images/buy1.jpeg" alt="">
   <img src="images/showp.webp" alt="">
   <img src="images/kb.webp" alt="">


CSS CODE CHANGES


Slider_section color changes from Blue to Black. This section is the first part of the website with the tag lines. (When you hover over the button it turns black instead of blue) 

.slider_section .carousel_btn-container .carousel-control-prev:hover,
.slider_section .carousel_btn-container .carousel-control-next:hover {
 background-color: #000000;
}



The service section background (It is used for the Products section of the website) got changed from Blue to Black. 

.service_section {
 background-color: #000000;
 color: #ffffff;
 text-align: center;
}



The client section (Reviews for my website) slider is used to toggle between reviews.  It was blue and now it's black. (When you hover over the button it turns black instead of blue)
 
.client_section .carousel_btn-container .carousel-control-prev:hover,
.client_section .carousel_btn-container .carousel-control-next:hover {
 background-color: #000000;
}


The footer_bg background image was changed from footer-bg to footer-blk. This changed the image of the blue footer to a black version of it. The footer is the image on the last part of the 


.footer_bg {
 background-image: url(../images/footer-blk.png);
 background-size: cover;
 background-position: right top;
 padding-top: 250px;
}




The hero_area’s background image was changed from hero-bg to hero-blk. (The picture behind the quality products , express shipping, etc tag lines.) It was blue now its black.

.hero_area {
 height: 98vh;
 position: relative;
 background-image: url(../images/hero-blk.png);
 background-size: cover;
 background-position: bottom;
}


The team sections backgrounds for the profile picture icons where changed from Blue to Black.
.team_section .team_container .box .img-box::before {
 content: "";
 position: absolute;
 z-index: -1;
 top: 0;
 left: 50%;
 width: 120%;
 height: 75%;
 border-radius: 25px;
 -webkit-transform: translateX(-52.5%) rotate(-15deg);
         transform: translateX(-52.5%) rotate(-15deg);
 background-color: #000000;
}
