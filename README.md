# lit-splat

A 3D Gaussian Splat viewer with dynamic lighting. Based on the [splat](https://github.com/antimatter15/splat) viewer by [antimatter15](https://github.com/antimatter15).

https://github.com/andrewkchan/lit-splat/raw/main/garden_demo.mov

## controls

movement (arrow keys)
- left/right arrow keys to strafe side to side
- up/down arrow keys to move forward/back
- space to jump

camera angle (wasd)
- a/d to turn camera left/right
- w/s to tilt camera up/down
- q/e to roll camera counterclockwise/clockwise
- i/k and j/l to orbit

trackpad
- scroll up/down/left/right to orbit
- pinch to move forward/back
- ctrl key + scroll to move forward/back
- shift + scroll to move up/down or strafe

mouse
- click and drag to orbit
- right click (or ctrl/cmd key) and drag up/down to move
- click and drag a light to move it in X and Y axes
- right click and drag a light to move it in Z axis

touch (mobile)
- one finger to orbit
- two finger pinch to move forward/back
- two finger rotate to rotate camera clockwise/counterclockwise
- two finger pan to move side-to-side and up-down

gamepad
- if you have a game controller connected it should work

other
- press M to switch between lighting mode and no lighting
- press N to switch between explicit normals and pseudo-normals
- press 0-9 to switch to one of the pre-loaded camera views
- press '-' or '+'key to cycle loaded cameras
- press p to resume default animation
- drag and drop .ply file to convert to .lsplat
- drag and drop cameras.json to load cameras