BuddyPress-Courseware-configuration
===================================

how to configure BP Courseware  with BP 1.7.2



Fisrt step is to edit groups.class.php to remove some issues 


Second u need to activate the forum from buddypress settings to activate BuddyPress-Courseware



Configure Courseware
======================

Warning: array_merge() [function.array-merge]: Argument #2 is not an array in /home/dougm196/public_html/nes/wp-content/plugins/buddypress-courseware/roles/roles.class.php on line 269

Warning: Invalid argument supplied for foreach() in /home/dougm196/public_html/nes/wp-content/plugins/buddypress-courseware/roles/roles.class.php on line 271


just Insert this code

ini_set(‘display_errors’,’off’);

on the top of this page, after the beginning php tag <?php

/wp-content/plugins/buddypress-courseware/roles/roles.class.php


Testimonials Widget
==========================


