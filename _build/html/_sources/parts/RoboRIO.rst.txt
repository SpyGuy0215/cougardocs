RoboRIO 2.0
=============
The RoboRIO is a robotics controller developed by National Instruments specifically
for FIRST. It is the second model of the RoboRIO, improving on the RoboRIO 1.0. 
The RoboRIO 2.0 is used to control all of the electronic components on the robot.

.. image:: images/roborio2.jpg
  :height: 350

Troubleshooting
---------------

Red Power Light
^^^^^^^^^^^^^^^^
If the Power light on the RoboRIO is red, it means that the RoboRIO is experiencing
a power fault. This could be caused by a number of things:

- One of the components connected to the ports on the RoboRIO is drawing too much
  power. Try connecting the components to the VRM instead
- One or more of the pins on the RoboRIO are being shorted. Verify that all
  connections are connected properly and secured