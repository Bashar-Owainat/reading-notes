## provide the function for each property of the following:
-	Mass: The object's weight (in kilograms by default).

-	Drag: How much air resistance an object experiences when moving due to forces. 0 means there is no air resistance, and infinity means the object immediately stops traveling.


-	Angular Drag: How much air resistance affects an object when it rotates due to torque. 0 indicates that there is no air resistance. It is important to note that simply setting the object's Angular Drag to infinity will not cause it to cease rotating.

-	Use Gravity: Gravity affects the object if it is enabled.

## what is the importance of rigidbodies?
Rigidbodies enable your GameObjects to interact with the physics engine. This opens the door to behaviors such as realistic collisions and a variety of joint kinds. Adding forces to a Rigidbody to manipulate your GameObjects produces a vastly different feel and look than modifying the Transform Component directly.

## what is the difference between Rigidbodies and manipulating the Transform?
Transforms cannot receive forces or torque, but rigidbodies can. It is possible to translate and rotate transforms, but this is not the same as using physics.
