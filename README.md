# BeepPanZoom
A hammer.js &amp;amp; Jquery based Touch Event Enabled Image Viewer Plugin with Pan and Pinch Zoom Support,
* Added Support for HTML MAPS, Which will auto postion and size anchros according to zoom level.
  Sample Usage:
  
  &lt;div class=&quot;img_cotainer&quot; style=&quot;overflow:hidden;width:100px;height:100px&quot;&gt;
  &lt;img src="assets/image.jpg"  usemap="#image-map"&gt;
  &lt;map name="image-map"&gt;
    &lt;area target="" alt="" title="" href="http://example.com/" coords="1909,3816,2026,4061" shape="rect"&gt;
  &lt;/map&gt;
  &lt;/div&gt;
    
Usage :

include jquery and hammer.js
include our js plugin

&lt;div class=&quot;img_cotainer&quot; style=&quot;overflow:hidden;width:100px;height:100px&quot;&gt;
&lt;img src=&quot;my_big_image.jpg&quot; style=&quot;width:inherit;height:inherit&quot; /&gt;
&lt;/div&gt;

Usage : 
$(&quot;.img_cotainer&quot;).beepPanZoom();


Some Options : 
ZOOM      : initial Zoom
MIN_SCALE : Minimum Allowed Scale
MAX_SCALE : Maxmium Allowed Scale


Example : 
$(".img_cotainer").beepPanZoom({ZOOM:1/2,
MIN_SCALE:0,
MAX_SCALE:5});


Sorry, too lazy right now...
