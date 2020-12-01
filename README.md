WebGL-Coursework is a second year project centered around WebGL and its javascript wrapper three.js. This particular coursework is authored by cct52. 

====================OPENING THE FILE========================

The html file should be able to run in any web browser, but it is recommended that you open it with Google Chrome, since the code was written and developed using Google Chrome. Web browsers automatically blocks usage of local files, so to get the full functionality of the code when running on your local machine, please 

1. Open command line (for windows) or terminal (for macOS or Linux)
2. Navigate into project file
3. Type in command "python -m http.server PORT" (<- replace PORT with a port number, i.e. 32007) to start a simple web server
4. On Google Chrome, type in "http://localhot:PORT" in the search bar to access the files (again, PORT is your port number, which must match the port number you typed previously)

You should see a textured cube positioned in the centre of a grid, with red, green, and blue axes if the html loaded correctly.

====================CAMERA CONTROLS=======================

1. Orbiting the camera about a point: HOLD down LEFT mouse key and DRAG
----------------------------------------------------
Drag left      |  camera goes right latitudinally  |
----------------------------------------------------
Drag right     |  camera goes right latitudinally  |
----------------------------------------------------
Drag up        |  camera goes down longitudinally  |
----------------------------------------------------
Drag down      |  camera goes up longitudinally    |
----------------------------------------------------

2. Translating the camera about its local axis: Press key button (See key mapping below)
----------------------
Move left      |  A  |
----------------------
Move right     |  D  |
----------------------
Move up        |  W  |
----------------------
Move down      |  S  |
----------------------

3. Resetting the camera: Press Q

4. Zoom in and out: Use mouse wheel
-----------------------------
Zoom in     |  Scroll down  |
-----------------------------
Zoom out    |  Scroll up    |
-----------------------------

====================ANIMATION CONTROLS====================

1. Playing and pausing rotation animation: Press SPACE

2. Rotate mesh about local axis: Press key button (See key mapping below)
-------------------------------
Rotate about x axis     |  X  |
-------------------------------
Rotate about y axis     |  Y  |
-------------------------------
Rotate about z axis     |  Z  |
-------------------------------
<!!!> When animation is paused, pressing X, Y, Z will automatically kick start the animation.

3. Resetting mesh position: Press R
<!!!> If animation is not paused, resetting will not pause the animation. Pausing -> resetting will reset mesh and stop it from moving.

====================MODE CONTROLS=========================

1. Changing the rendering mode of the mesh: Press key button (See key mapping below)
-----------------------
Face mode       |  F  |
-----------------------
Vertex mode     |  V  |
-----------------------
Edge mode       |  E  |
-----------------------

2. Toggling bewteen cube and Stanford bunny: Press B
<!!!> When cube is in vertex or edge mode, toggling to bunny will turn bunny into face mode, and visa versa

====================COSMIC STRING==========================

1. Enter cosmic string rendering mode: Press 0

2. Move camera: Move mouse pointer

3. Move light bulb: Move mouse pointer
<!!!> There's no way to return to previous render atm, refresh the page to return to the mesh.
