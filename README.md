ESC204 - Computer Vision
========================
This repository is for the <b>Praxis 3</b> design course in the second year <b>Engineering Science</b> curriculum at the <b>University of Toronto</b>. We design an automonous system to plug a charger into a parked electric vehicle.

This repository contains code used for locating the charger port, using python OpenCV. It also tracks modular progress of our electromechanical systems. Most of it is test code written for Arduino.

<br>

<center>

| Name      | Description            | Technical    |
|-----------|------------------------|--------------|
| cv        | identify charging port | opencv v4.00 with contribs, precompiled binary from `pip install`|
| insert    | plug insertion         | MG996R servo motor actuating a push-pull linkage to sliding tracks |
| leadscrew | side-to-side movement  | NEMA17 stepper motor with A4988 stepper motor driver|
| drive     | wheel motors           | 12VDC motor at 20RPM with 2x L298N DC motor drivers|

</center>
