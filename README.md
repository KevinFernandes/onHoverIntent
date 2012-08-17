This is a fork of the original JQuery plugin from Brian Cherne at http://cherne.net/brian/resources/jquery.hoverIntent.html.

The original version must bind to the intended targets of the JQuery selector where this version acts like the JQuery "on" 
method where you can specify a higher level selector, like a table, then filter the actual event on something below it.
The benefit of this method is that you can have the events on one element at a high level rather than on many elements.
This is useful where items that may require a hover event are added to the DOM dynamically, such as through Knockout.JS templates
or the like.

This was a simple change and as such, is provided for free and as-is.  I hope others may find it useful.

All credit for this plugin should be directed to Brian Cherne.