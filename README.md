jquery.drag.js
==============

Dragging elements easily with jQuery but without jQueryUI


Mainly based on the scripts and comments found there : http://css-tricks.com/snippets/jquery/draggable-without-jquery-ui/

I just added : 
- small corrections
- support for touch events
- a callback after each move
 

Usage : 
<div class="myThingToDrag">
  <div class="myHandle"></div>
</div>


$('div').drags({
    handle: ".myHandle",
    onMoved: function(){
      //do something cool
    }
  });
