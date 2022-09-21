# Multi-Functionality-Virtual-Mouse
This code presents a virtual mouse that has a number of functionalities that can be controlled through hand movement and gestures.

## Notation:
The fingers are numbered from 0 to 4 with the thumb being finger_0 and the pinky being finger_4.

## Available Functions:
- Default Pose: <br>
When you execute the code use this pose to ensure no unintended activation of a functionality. Then place your hand in the middle of the frame and lift finger_1 
<img src="/assets/images/Default_Pose.jpg" width="200">

- Mouse movement: <br>
You can move your mouse anywhere on the screen by lifting finger_1. Make sure that the other fingers are down in order to not interfere with the other functionalities.
<img src="/assets/images/Move_Mouse.jpg" width="200">

- Left Click: <br>
A quick flick of finger_0 will make one left click. Maintaining finger_0 up will press left click periodically (The time between presses is set in a was that prevents a "double click", if you need a double click you can reduce this cooldown time or implemented in another way).
<img src="/assets/images/Left_Click.jpg" width="200">

- Right Click: <br>
A quick flick of finger_4 whith all other fingers down will make one right click. Maintaining finger_4 up will press right click periodically.
<img src="/assets/images/Right_Click.jpg" width="200">

- Toggle Left Click: <br>
Having fingers from 1 to 4 up will toggle left click on. You can use this to drag items. When you lower fingers from 2 to 4 you will toggle off this functionality.
<img src="/assets/images/Drag.jpg" width="200">

- Scroll Up: <br>
Holding finger_1 and finger_2 up will toggle scroll up. The speed and distance of scrolling are parameters that can be changed as pleased.
<img src="/assets/images/Scroll_up.jpg" width="200">

- Scroll Down: <br>
Holding finger_1 and finger_4 up will toggle scroll down. The speed and distance of scrolling are parameters that can be changed as pleased.
<img src="/assets/images/Scroll_Down.jpg" width="200">

## Additional Remarks
* I tried to optimize this code as much as I could in order to have high FPS, however there is always more room for improvement.
* Try to experiment with this code yourself and set up your own functionality with any combination of fingers!
