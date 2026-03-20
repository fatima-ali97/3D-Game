## Tutorial 1 : Player & mouse movement (first person camera) 


[tutorial link](https://www.youtube.com/watch?v=Nxg0vQk05os&list=PLtLToKUhgzwnk4U2eQYridNnObc2gqWo-&index=1)


overview of what will be in the tutorial:

#### object heirarchy setup
1. create the following objects in the scene:

- terrain 
- player (empty 3D object)
    - inside the player create the cylinder 3D object.
     - move the camera object to the player object 
    - empty object called 'GroundCheck'


>[*notice*] move the camera on the top of the player and move 'GroundCheck' to the bottom of the player object (not just in the hierarchy but also in the actual player object!)


#### code for the playerMovement.cs & mouseMovement.cs
[PlayerMovement](https://gist.github.com/Mike-Schvedov/d916f7ff3b6d8b5f082c15b85d14fe30)

[MouseMovement](https://gist.github.com/Mike-Schvedov/b71316362691294e26bcdae6fc21696c)

copy the code from here - attach them to the player object

make sure to test if you can actually move your character!

if not here is a quick fix:
![alt text](image.png)