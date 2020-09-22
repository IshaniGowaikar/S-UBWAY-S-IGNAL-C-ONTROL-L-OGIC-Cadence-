# S-UBWAY-S-IGNAL-C-ONTROL-L-OGIC-Cadence-
The objective of this lab is to design a control logic block using Cadence.


Function:
Design a subway signal controller for each subway station. Each section of tracks in a subway station
will have a sensor to determine whether there is a train in that section and a signal with red, yellow,
and green lights.The light in the track section tshould show red if there is a train in the track
section in the very next station in the direction the train is traveling, yellow if there is no train in the
track section in the very next station but the section after that is occupied, and green otherwise.


Tracks allow trains move both ways from left to right and vice versa. The input D indicates the
direction allowed at the time. When it is 1, the left-to-right direction is allowed; when it is 0, the
right-to-left direction is allowed. The outputs G, Y, and R should be 1 to light the green, yellow, and
red signals, respectively. The input P is 1 if there is a train in this section (subway station). The signals
Ai, Bi, Ao and Bo are signal used to communicate from/to the station to the right and from/to the
station to the left. The signals Ai and Bi are received/sent from/to the section to the right of the
station, and signals Ao and Bo are received/sent from/to the section to the left of the station. You
may do with these what you like, but there are only two wires available, and you may not add more.
Therefore, they must have proper tri-state control. Based on your decision, specify how you will use
these two wires and what their functions are.

Inputs:
Ai, Bi, Ao, Bo: Inputs from the neighboring subway stations.
P: Sensor input to indicate existence of a train on the track.
D: Track direction input.
Outputs:
G, Y, R: Light control signals for green, yellow, and red lights, respectively.
Ai, Bi, Ao, Bo: Output signals for the neighboring stations.
