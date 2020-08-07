# Measuring change

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.


## Baseline vs interventions

<div class="juxtapose-container">
 <div class="juxtapose">
    <img src="img/baseline2.png" data-label="Baseline"/>
    <img src="img/intervention2_annot.png" data-label="Interventions"/>
 </div>
</div>
<script src="https://cdn.knightlab.com/libs/juxtapose/latest/js/juxtapose.min.js"></script>
<link rel="stylesheet" href="https://cdn.knightlab.com/libs/juxtapose/latest/css/juxtapose.css">


## Results

<div>
{% include mmap_edit.html %}
</div>
<br style="clear:both" />

*Here is a legend for the maps*

## And another section here
with some text again




<script>
var $juxtapose = $('.juxtapose'),
    $juxtapose_container = $('.juxtapose-container'),
    juxtapose_ratio;

$(window).load(function(){
  juxtapose_ratio = $juxtapose.outerHeight() / $juxtapose.outerWidth();
});

$(window).resize(function() {
  var new_width = $juxtapose_container.outerWidth(),
      new_height = new_width*juxtapose_ratio;

  $juxtapose.css({
    width: new_width,
    height: new_height
  })
});
</script>
