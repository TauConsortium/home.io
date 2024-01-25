---
layout              : page-fullwidth
show_meta           : false
title               : "Projects"
subheadline         : "Tau Consortium bioinformatic projects"
teaser              : "This site contains every Tau Consortium bioinformatic projects"
header:
   image_fullwidth  : "header_homepage_13.jpg"
permalink           : "/projects/"
---
<!-- head is made -->
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Popup</title>
    <link rel="stylesheet" href="{{ site.url }}{{ site.baseurl }}/assets/css/popups.css">
</head>

<div class="project-container">
   <div class="image-container">
      <img src="{{ site.url }}{{ site.baseurl }}/images/portfolio/acostauribe-2022.jpg" alt="Main Image" class="main-image">
      <div alt="Hover Image" class="hover-shape" onclick="showPopup('{{ site.url }}{{ site.baseurl }}/projects/popup_content.html')">
         <i class="icon-circle-with-plus"></i>
      </div>
   </div>
   <div class="project-title">
      <h3>Neurodegeneration in Colombia</h3>
      <h4 class="text-author"><em>WGS project</em></h4>
   </div>
</div>

<div id="overlayBackground" class ="overlay" onclick="hidePopup()"></div>
<!-- Popup content container -->
<div id="popupContainer" class="popup">
   <!-- Content will be loaded here -->
</div>

<!-- Link to the external JavaScript file -->
<script src="{{ site.url }}{{ site.baseurl }}/assets/js/popupscript.js"></script>