sizeyThingy
===========

Just a quick way of seeing what size your browser is, helps with Responsive design

Just include the jQuery library (http://jquery.com)

Then this file (jquery.sizeythingy.js)

in your HTML e.g.

<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.js"></script> 
<script src="assets/js/plugins/jquery.sizeythingy.js"></script> 

Then in your usual document.ready...


jQuery(document).ready(function() {
    jQuery.sizeyThingy(); 
)};

There are only 3 options...

sizeyThingyMessage: "W: "
This is just for the start of the information bar.

sizeyThingyRelative: false
This is to say "I want this to sit within the flow of html, e.g. at top, not overlaying anything".

sizeyForMobileRelative: true
If you're using a mobile/smart phone/tablet this allows you to switch off fixed positioning just for know mobile devices.

That's it - happy responsive designing :)