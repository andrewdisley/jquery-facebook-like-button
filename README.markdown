jQuery Facebook "Like" button
==============================

About
-----

A little Plugin to create a Facebook Like button with jQuery.

Source code is at http://github.com/henningthies/jquery-facebook-like-button.

Dependency
----------
You need jQuery.

How to Use
----------

Pick a html element and call the fbLike("your-page.com") on it.


Example
-------

For the html div:
  `<div id='facebook-like'></div>`

###simple:
  $('#facebook-like').fbLike("http://github.com");


###with options:
  var url = "http://github.com";
  $('#facebook-like').fbLike(url, {
    layout: "button_count",
    font: "lucida grande"
    color: "dark"
  }); 
Defaults
--------  
  scrolling: "no"
  frameborder: 0
  allowTransparency: true
  layout: "standard"
  show_faces: true
  width: 450
  height: 21
  verb: "like"
  font: "arial"
  color: "light"

License
-------
This library is provided via the GNU LGPL license at http://www.gnu.org/licenses/lgpl.html.

Author
------
Copyright 2010, Henning Thies <thies@ubilabs.net>, 
http://www.ubilabs.net.
