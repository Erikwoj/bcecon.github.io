---
layout: page
title: B.H. Choe - Home
description: Byeong-Hak Choe is a PhD candidate at University of Wyoming. 
keywords: Byeong-Hak, Choe, Economics
---
<div class="row-fluid">
    <div class="span3" style="padding-right:15px">
              <img src="../assets/bchoe20201027.jpg"
                           title="B.H. Choe" alt="B.H. Choe" align="right" />
    </div>
    <div class="span8 span12-tablet">
            Hello!<br>
            <br/>
            My name is Byeong-Hak Choe. I am a PhD candidate in Economics at University of Wyoming.<br>
            <br/>
            My research interests include analyzing the political economy of the environment with a particular focus on climate change, as well as designing new environment-economy models to demonstrate how the environment shapes the economy, and vice versa.<br>
            <br/>
            I am also interested in applying data science techniques for my research.<br>
            <br/>
            Here is my <a href="https://drive.google.com/file/d/1wrKIgrHOT1t9EnRgqCCEaVpOXxU_DJkY/view?usp=sharing" >curriculum vitae<img src="../pages/icons16/pdf-icon.png"
                           title="B.H. Choe" alt="B.H. Choe" align="middle" />.</a>
    </div>
</div>

<br/>
<br>

<!-- Slideshow container -->
<p style="text-align:center;">US map of social media campaigns with #climatechange/#globalwarming from 2012 to 2017</p>
<div class="slideshow-container">

  <!-- Full-width images with number and caption text -->
  <div class="mySlides">
    <div class="numbertext">1 / 6</div>
    <img src="../assets/n_campaign_2012.png" style="width:100%">
    <div class="text" style="color:indigo;">2012</div>
  </div>

  <div class="mySlides">
    <div class="numbertext">2 / 6</div>
    <img src="../assets/n_campaign_2013.png" style="width:100%">
    <div class="text" style="color:indigo;">2013</div>
  </div>

  <div class="mySlides">
    <div class="numbertext">3 / 6</div>
    <img src="../assets/n_campaign_2014.png" style="width:100%">
    <div class="text" style="color:indigo;">2014</div>
  </div>

  <div class="mySlides">
    <div class="numbertext">4 / 6</div>
    <img src="../assets/n_campaign_2015.png" style="width:100%">
    <div class="text" style="color:indigo;">2015</div>
  </div>

  <div class="mySlides">
    <div class="numbertext">5 / 6</div>
    <img src="../assets/n_campaign_2016.png" style="width:100%">
    <div class="text" style="color:indigo;">2016</div>
  </div>

  <div class="mySlides">
    <div class="numbertext">6 / 6</div>
    <img src="../assets/n_campaign_2017.png" style="width:100%">
    <div class="text" style="color:indigo;">2017</div>
  </div>
  <!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)" style="color:indigo;">&#10094;</a>
  <a class="next" onclick="plusSlides(1)" style="color:indigo;">&#10095;</a>
</div>
<br>

<!-- The dots/circles -->
<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
  <span class="dot" onclick="currentSlide(4)"></span> 
  <span class="dot" onclick="currentSlide(5)"></span> 
  <span class="dot" onclick="currentSlide(6)"></span> 
</div>


<script>
var slideIndex = 6;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}
</script>


<br/>

---

#### <a name="Contact"></a>Contact
<div class="container">
    <div class="row-fluid">
        <div class="span5">
            <b>Byeong-Hak Choe</b> <b>&nbsp;|&nbsp;</b> <a href="mailto:bchoe@uwyo.edu">bchoe@uwyo.edu</a><br>
            <br/>
            Department of Economics <br>
            College of Business Department 3985 <br>
            Laramie, WY 82071 USA <br>
            <br/>
            <br/>
            <font size="-1">Design forked from <a href="https://github.com/kbroman/kbroman.github.io">kborman</a> and <a href="https://github.com/mbcarlos/simple_academic_website">mbcarlos</a> & modified by <a href="https://github.com/bcecon/">bcecon </font>
        </div>
        <div class="span2" style="text-align:left">
        </div>
    </div>  
</div>

<br />
<div class="navbar">
  <div class="navbar-text">
      <ul class="nav">
          <li><a href="https://github.com/bcecon">github</a></li>
          <li><a href="https://www.linkedin.com/in/byeong-hak-choe-28471172/">linkedin</a></li>
          <li><a href="https://twitter.com/climate_econ">twitter</a></li>
      </ul>
  </div>
</div>
