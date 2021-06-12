# Flappy_Bird-OPENGL

#### SNAPSHOTS:

#### 1.INITIAL GAME:
![One](https://github.com/Jaisood08/Flappy_Bird-OPENGL/blob/main/4.png)
![Two](https://github.com/Jaisood08/Flappy_Bird-OPENGL/blob/main/3.png)

#### 2.BIRD:

#### 3.DURING GAME:


#### 4.PIPES


#### 5.MORNING AND NIGHT VIEW:

#### 6.BUILDING:


#### 7.MOUNTAINS AND CLOUDS:

#### 8. END OF GAME WITH SCORE DISPLAYED ON SCREEN:
![On](https://github.com/Jaisood08/Flappy_Bird-OPENGL/blob/main/2.png)
![To](https://github.com/Jaisood08/Flappy_Bird-OPENGL/blob/main/1.png)


Project Description
```
The project is based upon GLUT i.e. the OpenGL Utility Toolkit, a window system
independent toolkit for writing OpenGL programs. OpenGL is a cross-language, cross-
platform application programming interface for rendering 2D and 3D vector graphics.

It is similar to the famous Flappy Bird game made using OpenGL in C++. It uses the OpenGL
library GLUT and its various functions and functionalities along with C++ to give an
experience similar to the famous android game Flappy Bird. It is developed in visual studio
2019.

This project explores the use of physical law (gravitational law) for the game development.
The game in its exactness follows rules similar to that of the original game known as flappy
bird. The rules and regulation of the game are very basic and easy to understand. The game
scenario puts the player in control of a hovering bird with its wings flying in the screen with
moving obstacles of pipelines. The goal of the game is to get through the opening in the
obstacles without colliding into them. The game is implemented in C++. Also we have tries
implementing various graphics to make our game more attractive like buildings in the
background in addition with clouds and grass and flowers on ground and the morning to night
view while the player continue to play. The case study discusses the use of simpler motion and
modification to build the abstraction. The game is in single player mode. The user can interact
with the game using keyboard.

```
Objectives
```
We made this game or project so that we could give our best in possible ways and show what
we learned. The objectives of this project are:

- To play the famous game flappy bird in computer.
- To make it user friendly.
    - To provide an easy interface.
    - To entertain people in their leisure time.

```
Proposed System
```
The proposed system is designed to give a minimalistic and simplistic look and feel to the GUI
for Flappy Bird with lots and lots of new graphics. The control of the system is done with a
simple ↑ keystroke or by clicking the mouse.

Main Menu Window

- Start Game Option

Game Window

- Bird in downward motion and pipelines moving to the left
- Score Count


End Window

- Display final score.

Game play

Game play is very simple in Flappy Dot. The player has to move the bird through the pipelines
without colliding. If the bird collides with the pipelines the game will come to an end and the
final score will be displayed. If the bird lands on the base of the game it will also come to an
end. The basic idea for the player is to keep the bird untouched from any obstacles.

#### REQUIREMENTS.

The requirements can be broken down into 2 major categories namely hardware and

software requirements. The former specifies the minimal hardware facilities expected in a

system in which the project has to be run. The latter specifies the essential software needed

to build and run the project.

#### HARDWARE REQUIREMENTS

The hardware requirement is minimal and the software can run with minimal requirements.

The basic requirements are as enlisted below:

1. Processor: Intel 486 / Pentium processor or a processor with higher requirements.
2. Processor speed: 500MHz or above.
3. RAM: 64MB or above.
4. Storage space: 2MB or above.
5. Monitor resolution: A color monitor with a minimum resolution of 60*480.

#### SOFTWARE REQUIREMENTS

1.An MS-DOS based operating system like WINDOWS 98, WINDOWS 2000 or WINDOWS
XP or above windows platform is required to develop the 3D simulation.

2. A C/C++ (integrated with OPEN GL) compiler like Eclipse, Visual Studio etc is required to
compile the source code to make the executable file which can be directly executed.
3. A built in graphics library: glut.h is required for drawing layout of game.
4. glut32.d11 for running the application.


#### CONCEPT USED

OpenGL is a cross-language, cross-platform application programming interface for rendering
2D and 3D vector graphics. The API is typically used to interact with a graphics processing
unit, to achieve hardware-accelerated rendering. OpenGL libraries and various GL and GLU
commands were used in this project. These are as follows :

```
 glColor: Set the current color.
 glBegin and glEnd: Delimit the vertices of a primitive or a group of like primitives.
 glVertex: These functions specify a vertex.
 glReadPixels: Reads a block of pixels from the framebuffer.
 glRasterPos: Specify the raster position for pixel operations.
 glutBitmapCharacter: renders a bitmap character using OpenGL
 glClear(): Clears buffers to preset values.
 glFlush(): Forces execution of OpenGL functions in finite time.
 glMatrixMode: Specifies which matrix is the current matrix.
 glLoadIdentity: Replaces the current matrix with the identity matrix.
 gluOrtho2D: Defines a 2-D orthographic projection matrix.
```
GLUT provides high-level utilities to simplify OpenGL programming, especially in
interacting with the Operating System (such as creating a window, handling key and mouse
inputs). The following GLUT functions were used in the project:

```
 glutBitmapCharacter: renders a bitmap character using OpenGL
 glutInit: Initializes GLUT, must be called before other GL/GLUT functions. It takes
the same arguments as the main().
 glutInitWindowSize: Specifies the initial window width and height, in pixels.
 glutInitWindowPosition: Positions the top-left corner of the initial window at (x, y).
 glutCreateWindow: Creates a window with the given title.
 glutDisplayFunc: Registers the callback function for handling window-paint event.
The OpenGL graphic system calls back this handler when it receives a window re-
paint request.
 glutMainLoop: Enters the infinite event-processing loop, i.e, put the OpenGL
graphics system to wait for events, and trigger respective event handlers.
 glutTimerFunc: Registers a timer callback to be triggered in a specified number of
milliseconds.
 glutReshapeWindow: Requests a change to the size of the current window.
 glutCreateMenu: Creates a new pop-up menu.
```
Various other GLUT functions like glutAddMenuEntry, glutAttachMenu, glutReshapeFunc,
glutSpecialFunc, etc. are also used in the project code.


Polygon Drawing: -

● Circle: - The polygon constructed about the center with a particular radius using a loop over
the angle from 0 to 360 degree.

● Sphere: - The polygon using glutSolidSphere library

. ● Through Points: - Polygon is constructed by looping over different points in the space.

Lines: -

They are drawn using the library by mentioning starting and ending points (x, y coordinates)
in the space.

Polygon Filling: -

By using glcolor3f, we could fill colors inside any polygon by filling the RGB values.

User Interface Design : **–**

User interface (UI) design is the process designers use to build interfaces in software or
computerized devices, focusing on looks or style. Designers aim to create interfaces that users
find easy to use and pleasurable

.

Viewing : **–**

We used openGL for window to viewport transformation in 3D, which is another concept of
computer graphics.

Graphic Primitives : **–**

We used OpenGL to make various primitives of computer graphics such as rectangles, circles,
and other shapes for bird, pipes, clouds and buildings.


```
User Defined Functions
```
1. void Circle(float X, float Y, float r, int S, int Q): To draw all the circles including the
sun, moon and the flaps of the bird.

2.void Flap(float Y): It is used to draw the flaps of the bird.

3.void Bird(float Y): It is used to draw the bird including of circle its eyes ,body and lips.

4.void Rand(): This function is used to create the random values which are further used to
give the random positioning of the pipes.

5.void PIPE1(int X) : This function is used to create the pipe including of its two aligned
together.

6.void PIPE2(int X): This function is used to create the pipe including of its two aligned
together.

7.void PIPE3(int X): This function is used to create the pipe including of its two aligned
together.

8.void PIPE4(int X): This function is used to create the pipe including of its two aligned
together.

9.void GameCheck(int X): This function is used to check the status of the game whether the
bird touches the pole or if it doesn’t then it increases the count of the score.

10 .void SUN_MOON(float X, float Y): This function is used to create the sun and moon.

11.void Cloud(int X, int Y): This function is used to create the clouds in the sky.

12.void drawString(float x, float y, float z, string CH): To display text with

GLUT_BITMAP_TIMES_ROMAN_24 style and size.

13.void drawStringsmall(float x, float y, float z, string CH): To display text with

GLUT_BITMAP_HELVETICA_12 style and size.

14.void BACK(): This function is for background including buildings, grass , flowers,
mountain.

15.void display(): This is the main display function for displaying all the graphics

16.void Jump(int btn, int state, int x, int y): This is using glutMouseFunc() by clicking the
mouse the position of the bird increases by 2 pixels.

17.void Start(unsigned char key, int x, int y): The function glutKeyboardFunc() calls this
to start the game;

18.void myinit(): This function is used in initialising the matrix mode, gluOrtho2D(- 10 , 10 , -
10 , 10 ).

19.int main(int argc, char** argv): This function is used to declare the display, mouse and
keyboard function and creates the window for application.






