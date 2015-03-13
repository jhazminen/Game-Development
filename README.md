# Labyrinth-Isolation

A third-person shooter game heavily inspired by the Resident Evil 4 gameplay, complete with aim mode (right click) and no-reload automatic firing

Gameplay:
The gameplay is rather simple, the player starts off with a primary weapon, a M4 gun, and use the various resources in the level to escape
the labyrinth with the character's friends.

Player Character:
The player character is created through the Autodesk Character generator, since rigging and skinning manually in Blenderx64 made the character harder to animate with the free animations provided in unity and it took too much of the valuable time. Since in the original Stealth game, where most of the assets were taken, the game view is in top-down angle and always points to the positive z direction, I had to change the controls to mostly that of a first-person shooter game. The gun rig was taken from one of the other completed games in unity namely, Bootcamp, and I attached it to the character player that I have by creating a new game object and used the shoulder down to the arms transform to create the left and right grips. The animations and sound effects were also taken from some of the unity projects, including the walk animation and the shooting sound effects. There is also a dying animation, although it only affects the character player, not the gun rig attached to it, so if the character dies, the gun remains in midair. In the animation, I created 3 layers, the Base, Upper body, and Lower body. The upper and lower body also uses an upper body mask and lower body mask, this prevents the animations from overlapping with each other during execution. The backgground music and some of the game settings were also from the Stealth game. The scripts were also written by me with the help of Unity forums and YouTube, since just implementing the pre-written scripts would not make me understand what I'm doing and would eventually mess up my game. 2 of the scripts were taken in the internet though, the Character Motor script and the Headlook Controller. This mainly controls the locomotion of the character and the headlook would make the character's head follow where the camera points at, a nice touch that would make the character look more natural.

Others:

Alarm Systems:
Mostly from the Stealth tutorials, this part of the game is mainly a practice with which I learned how colliders work and activates with various external events that would trigger those in the written code.

Environment:
An environment taken from the Stealth project since it fits nicely with the underground theme of the game, it is baked with dual lightmaps instead of dynamic because I'm using the free version of Unity, and Dynamic is only allowed in the pro version.

Key Item:
The item that would serve as the key that would open the lift that would end the level is a keycard.
Supposed to be, the game would have six more characters, which the player will have to find, protect, and they would follow the player character around and missing one would prevent the player from finishing the game. The designs for these characters were already finished although not included.
