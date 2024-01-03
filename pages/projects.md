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

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Popup</title>
    <link rel="stylesheet" href="../assets/css/popups.css">
</head>
<div class="image-container">
   <img src="../images/portfolio/acostauribe-2022.jpg" alt="Main Image" class="main-image">
   <div><i class="fa fa-plus fa-3x">+</i></div>
   <img src="../images/gallery-example-2.jpg" alt="Hover Image" class="hover-image" onclick="showPopup('{{ site.url }}{{ site.baseurl }}/projects/popup_content.html')">
</div>

<div id="overlayBackground" class ="overlay"> </div>
<!-- Popup content container -->
<div id="popupContainer" class="popup">
   <!-- Content will be loaded here -->
</div>

<!-- Link to the external JavaScript file -->
<script src="../assets/js/popupscript.js"></script>