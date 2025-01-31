=== Plugin Name ===
Contributors: kdclabs
Donate link: http://www.kdclabs.com/
Tags: Rupee, India Rupee, Rupee Symbol, India Rupee Symbol, Rs.
Requires at least: 2.6.3
Tested up to: 3.5.1
Stable tag: 1.0.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

WP WebRupee provides a simple, cross browser method for using the Rupee symbol on your WordPress. It converts all the Rs / Rs. symbol to Rupee Symbol.

== Description ==

It converts all the Rs / Rs. symbol to Rupee Symbol.
This Rupee symbol is dynamically generated by WebRupee API for web viewing. It's not an image. The visitors to your website do not require a special font installed at their end. Its our try to contribute to our nation's success.

Visit [www.kdcLabs.com](http://www.kdclabs.com/?p=74 "_KDC-Labs : WP WebRupee") for more info about this plugin.


== Installation ==

1. Unzip and upload contents of the plugin to your `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

= Configuration =

* This plugin does not require any Configuration.
* It converts all the Rs / Rs. symbol to Rupee Symbol.

== Frequently Asked Questions ==

= What browsers are supported? =

The WebRupee API is compatible with the following browsers:

* Mozilla Firefox: version: 3.5+
* Google Chrome: version 4.249.4+
* Apple Safari: version 3.1+
* Opera: version 10.5+
* Microsoft Internet Explorer: version 4+
* ... generally a WebKit Browser

= What would unsupported browsers show? =

If a user having an unsupported browser visits a page which uses WebRupee API, then he would see "Rs or Rs." depending on what the page previously displayed.

= Can I use other CSS features with Rupee Symbol generated by WebRupee? =

Yes, The rupee symbol generated by WebRupee is like anyother text in a page, you can very well apply any of the CSS properties like color, text-shadow, font-size etc.

= Will WebRupee slow down my page? =

If a page is using WebRupee API, then the font files are downloaded to the site visitors computer and then the browser uses it. The files which are downloaded are less than 5KB. Once downloaded these font files are cached by the browser. So if a visitor visits a page next he is likely to have that font files already.

= What if WebRupee doesn't work for any reason? What would visitors see? =

A visitor would see "Rs / Rs.". WebRupee looks for "Rs / Rs." and converts it to the Rupee Symbol. So if for some reason WebRupee fails, it will not be able to turn "Rs / Rs." to Rupee Symbol. So the visitos would see "Rs / Rs."

= What licensing terms are associated with WebRupee? =

WebRupee is Licensed under the Apache License, Version 2.0 (the "License"). 
Please visit [WebRupee.com](http://webrupee.com/license.html) for details.

== Screenshots ==

1. Converts any font Rs / Rs. symbol to Rupee Symbol

== Changelog ==

= 1.0.2 =
* Shiffted to the original Code hosted on webrupee.com 's CDN.

= 1.0.1 =
* Corrected *wp_enqueue_style* to *wp_enqueue_script* for loading JS

= 1.0.0 =
* First Public Release.
