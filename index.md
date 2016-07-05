---
layout: default
title: Home
---
<!-- #TODO: Move CSS to external file -->
<!-- #TODO: Create .center class -->
<style>
h1 { text-align: center; }
h2 { text-align: center; }
</style>

# 5points Percussion

## San Antonio's Newest Independent Indoor Percussion&nbsp;Ensemble

5points is a theatrical percussion ensemble based in San Antonio.&nbsp; We were founded in 2015 with a mission of enriching the lives of Texas youth through the indoor percussion activity.&nbsp; Our goal is to provide the 5points family with music education, performance opportunities, and a positively life-changing&nbsp;experience.
<img id="img960" src=""/>

<!-- #TODO: Use non-breaking hyphen for "life-changing" -->
<!-- #TODO: improve word spacing and line break on last word of the paragraph -->
<!-- #TODO: Get recent pictures and improve image carousel -->
<!-- #TODO: Do Facebook and Instagram links on footer disappear on refresh? -->
<script>
var imgDir = './public/img/960/';
var images = [];
images[0] = imgDir + 'home-0.jpg';
images[1] = imgDir + 'home-1.jpg';
images[2] = imgDir + 'home-2.jpg';
images[3] = imgDir + 'home-3.jpg';
var index = Math.floor(Math.random() * (images.length - 1));
document.getElementById('img960').src = images[index];
// #TODO: Use LocalStorage or SessionStorage to avoid duplicates in a random sequence
// #TODO: Place images at the bottom of other pages?
</script>
