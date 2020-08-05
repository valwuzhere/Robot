# Robot
Autonomous beacon-searching robot

This robot is put into a 2m x 2m enclosed arena. In the arena, there is a beacon that emits infrared lights. The robot is able to pick up the light, move towards the object, connect a wire to it, pull away tangle - free, and signal completion. As well as that, the robot is able to avoid walls and come out of corners.


This is a creation build out of VEX parts and coded by a team of three in ROBOT C for a class project for the University of Victoria.

- The robot is paired with two IR sensors on each side of the robot which work with an algorithm to detect the emitted light and find the center center of the robot. As soon as it is centered, the robot approaches the beacon and lowers its arm. 
- If the beacon is moved, the robot is able to pick this up and it starts turning in cirles to find the emission again.
- If the robot encouters a wall, it is able to pick this up with two limit switches on its sides. It then backs up and continues to search for the beacon by turning in circles.
- The beacon has a magnetic top and a magnet loosely attached to the arm. Once the arm is lowered, it waits a few seconds to ensure connection. The arm is the raised, the robot backs up, lowers the arm again to escape entanglement, backs up more, and then signifies completion with an LED on top. It is encased in cardboard to imporve its ability to untagle from the wire.
- The wire is fed to the robot from a spool outside of the arena.
