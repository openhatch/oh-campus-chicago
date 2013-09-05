Background
----------

The HTML document is comprised of alternating-styled sections.

All the section divs are "div.section" in CSS selector terminology.

The odd ones (including the first one) are also "div.colored".

The even ones (including the signup one) are not div.colored, so they
inherit text color and background color from the body tag.


How-to
------

First, style the colored section by editing:

* div.colored color /* text color */
* div.colored background /* background color */
* div.colored a color /* link color */
* h1 color /* heading color */

Then, style the rest by editing:

* body color /* main text color */
* body background /* main text background color */
* a color /* link color */


Useful tools
------------

* http://hexcolor.com/ -- you can paste CSS colors in here to see them
