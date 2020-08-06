# Yet another test
 
"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

## The Juxtapose method

<div class="juxtapose">
    <img src="img/baseline2.png" />
    <img src="img/intervention2_annot.png" />
</div>
<script src="https://cdn.knightlab.com/libs/juxtapose/latest/js/juxtapose.min.js"></script>
<link rel="stylesheet" href="https://cdn.knightlab.com/libs/juxtapose/latest/css/juxtapose.css">

## Modelling interventions

<div class="img-comp-container">
  <div class="img-comp-img">
    <img src="img/baseline2.png" width="700" height="495">
  </div>
  <div class="img-comp-img img-comp-overlay">
    <img src="img/intervention2_annot.png" width="700" height="495">
  </div>
</div>

<br style="clear:both" />

## Results

Explore the map!

<div>
{% include mmap_edit.html %}
</div>
<br style="clear:both" />

*Here is a legend for the maps*

## And another section here
with some text again



<script>
/*Execute a function that will execute an image compare function for each element with the img-comp-overlay class:*/
initComparisons();
</script>
