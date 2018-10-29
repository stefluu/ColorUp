# ColorUp

Background and Overview:

* `ColorUp` is a single player game in which the end goal is to build a path up to a door at the top of each level, which leads to the next level.

* The player will start at the bottom of the level on a blank canvas, and have control over the direction in which the can "draw". The direction will be indicated by an arrow pointer.

* "Drawing" is accomplished by selecting a direction upon mouseclick. This will shoot out multiple lines, the lines curving it if encounters the edge of the canvas, or any other line.

* The player may jump onto these lines, triggering coloration along the lines they walk upon. They progressively "draw" more to build a path up to the door.

* Each level, the door will be further away or situated in different orientations.

* Only the last 2 draws will be saved, all others will disappear. If the player falls, they will need to recreate paths from the bottom of the canvas.

Functionality and MVP Features

* Players can: 

    - Use mouse to select direction of "draw" action
    - "Draw" paths upon mouse-click 
    - Jump upon created paths
    - Enter a new level

* "Draw" path:
    - Can be drawn in any direction
    - Will colorize when player walks near it
             

Architecture and Technologies

* Vanilla Javascript - for logic
* HTML5 Canvas - for rendering

Implementation Timeline