This repository demonstrates how to control six servo motors with an Arduino Uno and outlines a simple walking algorithm for a humanoid robot. The two main parts are:

1- Servo Sweep & Hold

- Run a “sweep” motion (0° → 180° → 0°) on all six servos for approximately 2 seconds.

- Immediately after, hold each servo at 90° indefinitely.

2- Humanoid Walking Algorithm (Pseudo-Code)

- Define the sequence of leg movements for one walking step:

1. Lift right leg (hip & knee servos adjust to predefined angles)

2. Swing right leg forward

3. Lower right leg and shift weight

4. Repeat the same for the left leg

- Loop the above until the robot reaches its target.
