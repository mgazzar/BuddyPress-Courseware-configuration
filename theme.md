edit the slider follow these instructions
============================================
Tried also add lines into the child css like

.carousel .item {
line-height: 380px;
overflow: hidden;
min-height: 880px;
}
.carousel-image {
position: absolute;
top: 0;
left: 0;
min-width: 100%;
height: auto;
}
.carousel-image img {
width: 100%;
height: auto;
/* max-height: 100%; */
}

http://wordpress.org/support/topic/slider-height-3/page/2

edit the navbar 
==============================================

.navbar .nav > li > a {
color: COLOURVALUE;
}

http://wordpress.org/support/topic/change-color-of-words-in-menu?replies=4


to edit the upper menu
======================

.navbar .nav > li > a {
  float: none;
  padding: 10px 15px 10px;
  color: #777777;
  text-decoration: none;
}





enhancing the drop shadow
=========================

 -moz-box-shadow: 0 0 5px #888;
-webkit-box-shadow: 0 0 5px#888;
box-shadow: 0 0 5px #888;
http://www.css3.info/preview/box-shadow/


to edit post 
====================================
remove this line form
C:\xampp\htdocs\xxxx\wp-content\themes\customizr\parts\class-content-post.php

  <div class="tc-content <?php echo $content_class; ?>">
      
remove post thum
===================
C:\xampp\htdocs\xxxx\wp-content\themes\customizr\parts\class-content-post.php

 add_action  ( '__post_thumbnail'        , array( $this , 'tc_content_post_thumbnail' ));

Remove Disable ToolBar Removal
=============================

http://wordpress.org/plugins/wp-toolbar-removal/screenshots/


update the upper nav
====================
in line 5300
navbar-wrapper class
