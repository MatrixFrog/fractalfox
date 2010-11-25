This is just a little Firefox addon to show how Mozilla's XBL technology can be
used to create fractals with minimal effort. Essentially, a level `N` 
(Sierpinski triangle)[http://en.wikipedia.org/wiki/Sierpinski_triangle] is made
up of three level `N-1` triangles, except for the level 0 triangle, which is 
simply a triangle. XBL makes it easy to draw the triangle. For example, to create
a level 4 Sierpinski triangle, just put the following element into your UI:

    <sierpinskiTriangle level="4" />

To use the extension, just select "Sierpinski Triangle" from the Tools menu, then
use the textbox at the top of the page to adjust the level. Enjoy!
