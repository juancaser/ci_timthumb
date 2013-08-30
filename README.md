CI_Timthumb
===========

A timthumb CI controller implementation

Uses timthumb by Ben Gillbanks and Mark Maunder. Based on work done by Tim McDaniels and Darren Hoyt http://code.google.com/p/timthumb/

GNU General Public License, version 2: http://www.gnu.org/licenses/old-licenses/gpl-2.0.html

For timthumb Examples and documentation available on the project homepage: http://www.binarymoon.co.uk/projects/timthumb/

How to use
==========

 <img src="<?php echo base_url(array(
		'thumbnail', // Controller name
		rawurlencode(base64_encode('http://ellislab.com/asset/css/img/')), // Image path/url
		'100', // Settings Width x Height
		'logo.png?q=1&zc=1'	
	));?>" />
