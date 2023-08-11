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

## Computer Graphics concepts used
•     OpenGL:  The  project  is  developed  using  the  OpenGL  graphics  library, which is a 
powerful cross-platform API for creating 2D and 3D graphics.  
•     GLUT: The utility toolkit for OpenGL is used in this project for creating graphical user 
interfaces and handling user input.  
•     Drawing tools: The project includes basic drawing tools such as lines, air brush, and 
erasers, which allow users to create different types of lines and
shapes.  
•     Colours:  The  project  allows  users  to  select  different  colours  for  their
drawings, which are represented using the RGB (Red-Green-Blue) colour
model.  
•     Coordinate system: The project uses a  coordinate system to represent the
position of objects on the canvas.  
•     Shapes:  The  project  allows  users  to  create  different  shapes,  such  as rectangles, 
circles, and polygons.  
•     Transformations:  The  project  includes  transformation  functions  that  scale objects on 
the canvas.  
•     Clipping: The project removes parts of a drawing that fall outside of a specified
region.  
•     Keyboard shortcuts: The project uses keyboard shortcuts to allow users to
perform basic operations quickly and efficiently.  
•     Rendering: The project uses rendering techniques to display the graphics on the screen, 
including rasterization.  
•     Line drawing algorithms: The project includes algorithms for drawing lines, such as 
Bresenham's algorithm.  
•     Circle  drawing  algorithms:  The  project  includes  algorithms  for  drawing circles, such 
as Mid point algorithm.  
•    Polygon drawing algorithms: The project includes algorithms for drawing
polygons. 


## User Defined functions
1.   normX(),  normY():  Normalize  the  coordinates  from  screen  coordinate  system  to  device
coordinate system.
2.   getRadius():  Find the radius of the circle using Euclidean distance.
3.   drawPoint(): To draw a point with coordinates x,y.
4.   drawLine(): To draw a line between two points.
5.   drawRectangle(): To draw a rectangle.
6.   drawCircle(): To draw a circle with radius r and centre at x,y.
7.   draw_polygon(): To draw a polygon such as pentagon and hexagon.
8.   clearScreen(): To clear all the contents on the screen.
9.   drawBrush(): To paint using airbrush.
10. erase(): To erase the drawing or any portion of drawing.
11. randColor(): To choose a random colour from a list of pre-defined colours.
12. initMenu(): List the available options in program.
13. menu(): Map each available option to its respective case.
14. MixMatch(): To call display(), keyboard(), mouse() and motion() functions.





