---
layout: page
title: Home
---

<script type="text/javascript">
  let mutor_unit_color = MUTOR.rbright();
</script>

# History and Practice of Multimedia - Online Lecture Series

Welcome to the MUTOR series on the History and Practice of Multimedia! 
The materials collected here were originally presented as a 12-part
online lecture series in 2021. In the "Units" section of this site,
you will find the text and 
supporting media for each talk, as well as recordings of the talks
themselves. 

This lecture series is part of the Hamburg Open Online University (HOOU) 
and serves as the basis for a new class within the 
Music Technology Online Repository (MUTOR).

<!-- <div class="left" style="display:inline-block; vertical-align:top; padding-top: 100px;"> -->
<div>
  <span class="burger-menu" onclick="openNav()">
    <!-- <h1 id="gotounits" style="cursor: pointer;">Go to Units</h1> -->
    <span href="" id="gotounits" style="cursor: pointer;">Go to Units</span>
    <script type="text/javascript">
      let gtu = document.getElementById("gotounits");
      gtu.style['background-color'] = mutor_unit_color;
      <!-- gtu.addEventListener('mouseenter', function(){ -->
	  <!-- 	this.style.background = '#FF0000'; -->
	  <!-- }); -->
	  <!-- gtu.addEventListener('mouseout', function(){ -->
	  <!-- 	this.style.background = '#FFFFFF'; -->
	  <!-- }); -->
    </script>
  </span>
</div>
<!-- <div class="right" style="display:inline-block;"> -->
<div class="slideshow-wrapper">
  
  {% for u in site.units %}
  {% assign uu = u.number | split: "." %}
  {% if uu.size == 1 or uu[1] == "1" %}
  <div class="slideshow-slide slideshow-fade">
    <!-- <div class="slideshow-numbertext">{{ u.number }}</div> -->
    <img src="./assets/images/flyers/{{ u.flyer }}" style="width:100%">
    <!-- <div class="slideshow-caption">{{ u.title }}</div> -->
  </div>
  {% endif %}
  {% endfor %}
  
  <a class="slideshow-prev" onclick="changeslide(-1)">&#10094;</a>
  <a class="slideshow-next" onclick="changeslide(1)">&#10095;</a>
  
</div>
<br>

<div style="text-align:center">

  {% for u in site.units %}

  {% assign uu = u.number | split: "." %}
  {% if uu.size == 1 or uu[1] == "1" %}
  <span class="slideshow-dot" onclick="setslide({% increment dotnum %})"></span>

  {% endif %}
  {% endfor %}
  
</div>
<!-- </div> <\!-- right -\-> -->

<script type="text/javascript">
  var slideindex = 1;
  showslides();

  // Next/previous controls
  function changeslide(n)
  {
    slideindex += n;
  	<!-- showslides(); -->
  }

  // Thumbnail image controls
  function setslide(n)
  {
    slideindex = n + 1
  	<!-- showslides(); -->
  }

  function showslides()
  {
  	var i;
  	var slides = document.getElementsByClassName("slideshow-slide");
    var dots = document.getElementsByClassName("slideshow-dot");
    if(slideindex > slides.length)
    {
  		slideindex = 1;
    }
    if(slideindex < 1)
    {
        slideindex = slides.length
    }
    for (i = 0; i < slides.length; i++)
    {
    	slides[i].style.display = "none";
    }
    for (i = 0; i < dots.length; i++)
    {                                
    	dots[i].className = dots[i].className.replace(" active", "");
    }
    slides[slideindex - 1].style.display = "block";
    dots[slideindex - 1].className += " active";
    ++slideindex;
    
    setTimeout(showslides, 4000);//, slideindex);
  }
</script>
