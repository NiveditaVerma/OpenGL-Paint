# OpenGL-Paint
This project is a simple paint tool developed using C++ programming language with the OpenGL/GLUT library. It provides basic functionalities for drawing and painting on a canvas similar to Microsoft's Paint application. The project aims to provide a user-friendly interface and easy-to-use tools for drawing shapes, lines, and polygons. It also allows users to choose between a wide range of colors to draw. In addition to its intuitive interface and user-friendly features, this project also includes an added functionality of operating with the help of keyboard shortcuts. This feature provides users with quick and easy access to basic operations, making the painting process even more efficient and streamlined.
## Following are the operations performed in the program:
Mouse event:  
Right click -> show menu, Left click -> choose option.

Menu:
1.   Colour -> User can choose Red, Green, Blue, White or Random.
2.   Shapes -> The default shape is Point.
o  Point -> draw a dot at the point clicked with the mouse. Clicking and dragging will draw points 
constantly like free-form drawing.
o  Line -> draw a line between two subsequently clicked points
o  Rectangle  ->  draw  a  rectangle  with  top-left  corner  specified  by  the  first  click  and 
 the bottom-right corner specified by a second click.
o  Circle -> draw a circle centered at the position of the first click, with its radius set by a
second click.
o  Airbrush -> draw multiple points as brush around the clicked point. There are four options
of size.
o  Eraser -> erase the points by clicking and dragging.
3.   ClearScreen -> clear the screen.
4.   Quit -> close the window.


Keyboard events:
1.   q or esc -> close the window.
2.   c -> clear the screen
3.   r -> choose red color.
4.   g->  choose green color.
5.   b -> choose blue color.
