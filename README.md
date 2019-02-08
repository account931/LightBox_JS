# LightBox_JS - JS plugin for images gallery, opens a clicked image in full screen modal window

How to use:

1.Wrap images to one div class="thumbnails">
2. Init Lightbox div:  $(function() { $('#thumbnails a').lightBox(); });



VARIANT 2 (UNTESTED)
=============================================================
OR You can try this LightBox(below), usage is a bit different from above.Below LightBox is not tested yet.
https://lokeshdhakar.com/projects/lightbox2/

Initialize with HTML
1.Single images. Add a data-lightbox attribute to any image link to enable Lightbox. For the value of the attribute, use a unique name for each image. For example:
<a href="images/image-1.jpg" data-lightbox="image-1" data-title="My caption">Image #1</a>

2.Image sets. If you have a group of related images that you would like to combine into a set, use the same data-lightbox attribute value for all of the images. For example:
<a href="images/image-2.jpg" data-lightbox="roadtrip">Image #2</a>
<a href="images/image-3.jpg" data-lightbox="roadtrip">Image #3</a>
<a href="images/image-4.jpg" data-lightbox="roadtrip">Image #4</a>
 
