SnailSlider

SnailSlider uses the JQuery library to make a simple slider application that can live on a web page. It is free to use!

The basic setup is as follows:

#Include the stylesheet, JQuery, and snailslider.js:

<link rel="stylesheet" href="snailslider.css"/>
<script type="text/javascript" src="/App_Assets/js/jquery/jquery-1.10.1.min.js"></script>
<script type="text/javascript" src="snailslider.js"></script>

#Put this in your page html
<div id="slider-wrapper">
     <div id="slider-inner">
          <div id="slide-canvas" name="slide_canvas">
               <div>
                    <img src="milkyway.jpg"/>
               </div>
               <div>
                    <img src="empty-field.jpg"/>
               </div>
               <div>
                    <img src="hyper.jpg"/>
               </div>
               <div>
                    <img src="railway.jpg"/>
               </div>
               <div>
                    <img src="road.jpg"/>
               </div>
          </div>
     </div>
     <div id="slider-control">
     </div>
</div>

Each image you put in will be automatically added in the order you include them, they must be wrapped in <div> tags though. So to add a new image:

<div><img src="image.jpg" /></div>

Included in the package is a html file that is set up to display the slider.