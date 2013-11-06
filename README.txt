MouseToTUIO
-----------
Overlay for Processing that converts mouse events to TUIO messages

Introduction:
-------------
MouseToTUIO simulates a virtual table and provides a multi-touch finger tracking
simulation. It tracks the ID, position and orientation of virtual touches
on a virtual table surface. This data is sent via a network 
connection to any client application. It implements the TUIO protocol,
which is based on Open sound control.

Application:
------------------
This application is based on the Java programming language.
It needs a Java Runtime Environment version 1.5 or later 
installed on your system in order to function properly.
See: http://java.sun.com/j2se/

The default TUIO host is 127.0.0.1 (localhost)
The default TUIO port is 3333.

* Simple mouse-dragging on the table creates cursor events

* Press SHIFT while dragging to create a sticky cursor 

* Continue to manipulate any sticky cursor by moving its gray area 

* Remove sticky cursors by SHIFT clicking in its area 

* Press CTRL while dragging to add a cursor to a group

* Moving any cursor of a group will move the other group members

* Remove cursors from a group by CTRL clicking in its dark gray area 

References:
-----------
This application uses the JavaOSC OpenSound Control library.
See http://www.mat.ucsb.edu/~c.ramakr/illposed/javaosc.html
for more information and the source code.

This application uses a stripped down version of the reacTiVision
TUIO simulator. 
See http://reactivision.sourceforge.net/ 
for more information and the source code.

License:
--------
  Modified version of TUIO Simulator - part of the reacTIVision project
  http://reactivision.sourceforge.net/

  Copyright (c) 2005-2009 Martin Kaltenbrunner <mkalten@iua.upf.edu>
 
  This version Copyright (c) 2011 
  Erik Paluka, Christopher Collins - University of Ontario Institute of Technology
  Mark Hancock - University of Waterloo
  contact: christopher.collins@uoit.ca

  This library is free software; you can redistribute it and/or
  modify it under the terms of the GNU General Public
  License Version 3 as published by the Free Software Foundation.

  This library is distributed in the hope that it will be useful,
  but WITHOUT ANY WARRANTY; without even the implied warranty of
  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
  General Public License for more details.

  You should have received a copy of the GNU General
  Public License along with this library; if not, write to the
  Free Software Foundation, Inc., 59 Temple Place, Suite 330,
  Boston, MA  02111-1307  USA
