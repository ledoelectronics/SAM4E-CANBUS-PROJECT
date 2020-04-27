# SAM4E-CANBUS-PROJECT
SAM4E and WAGO PLC 750-337 Communication Example

The example shows the use of the CAN Bus interface present on the ATSAM4E-16C chip, for communication with three different nodes:
1.	WAGO PLC 750-337
2.	CAN IO Board from Ledoelectronics
3.	CAN Motor Board from Ledoelectronics



 
The CAN Bus is extraordinary. It speed is only 1 Mbit / s, and only 8 bytes can be transmitted in each message. Even so, it is the standard of communication between elements of machines; used in almost all vehicles on earth and space.
It is Event driven. Each node can initiate a transaction to be attended when needed. It has an arbitrariness system, which handles possible collisions, based on the priority of the messages.
It is a redundant system by Hardware and Software. It has the highest immunity to noise among all existing communication buses.
It was developed by the German company Robert Bosh GmbH in the mid-1980s.
This application shows the CAN communication functionalities of the module
SAM TFT4.0 TOUCH from Ledoelectronics. It allows interaction with three nodes on a CAN bus.
• With the Wago 750-337 PLC
• With the CAN IO module from Ledoelectronics
• With the Ledoelectronics CAN Motor module

