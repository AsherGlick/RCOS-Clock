What is the RCOS Clock
----------------------
The RCOS Clock is a project that I started about a year ago, developing different  
cheap ways to create seemingly high quality hardware using simple rapid prototyping  
techniques. 


Plan of Action
--------------
Etching Method: Toner Transfer Method  
Finish Method: I have had good results with this method from painting computer  
cases but I am unsure how it will work on plexiglass/fiberglass  

* matte finish for color
* glossy coat for finial

Logos will be etched in copper then protected when color is being added  
Gloss will then cover the logo
Sand Corners to slightly round the board

Schedule
--------
I have not developed a circut board from start to finish without help before so  
I am unsure on how long it will take  

* Design schematic for the clock
* Design code for the clock
* Test methods of finishing (gloss spraypaint, epoxy, dyes) on circut plexiglass/fiberglass
* Obtain parts
* Laser cut opensource sticker images to prevent finish from covering etched copper 
* Get Photopaper
* Etch circut board
* Apply Chosen Finish method to front of board
* Solder board
* Testing phase for code
* Apply chosen finish method to back of board
* Done

Features
--------
Wall powered with a long brightly colored power adapter (guess what color)
Opensource + Open hardware logos
Five visible digits (00:00.0)
Green/Red bicolor LEDs
Large enough to be seen from the other side of the room (~10m should be good)
Buttons!
Name       | Function
-----------|---------------------------------------------------------------------------------------------------------
+1 minute  | Adds one minute to the timer
-1 minute  | Subtracts one minute from the timer
+5 minutes | Adds five minutes to the timer
+10 minutes| Adds ten minutes to the timer
undo       | Reverts the clock back to the state before the last button was pressed (including the start/stop button)
redo       | redos whatever undo did
start/stop | starts the count if stopped, stops the countdown if started
reset clock| resets the clock to the last time. If pressed twice it resets to 0
