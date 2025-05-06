Freelance Container Ship (5000 TEU) and STS crane
for Microsoft Train Simulator

Original Freeware Model by Marek Lemow (Copyright 2013)


===============================================================================
1. DETAILS
2. INSTALL INSTRUCTIONS
3. ACKNOWLEGMENTS
4. MODEL INFO
5. TERMS OF USE, DISCLAIMER & LEGAL STUFF
===============================================================================

1. DETAILS

This is a freelance representation of a 5000 TEU Class container ship used to 
transport shipping containers around the globe.

Typical specifications for a ship that this model is based on are:

Length:            270m

Beam:              40m

Max draught:       13.5m

Deadweight:        74,000 metric tonnes

Fuel consumption:  152 tons of fuel per day at service speed of 23.2knots

Range:             24,000 nautical miles

Main Engine:

1 x 6 cylinder marine diesel engine, turbo charged with Max continius rating of
42,100kW at 104 rpm driving a single 5 bladed propeller.

A simple STS (Ship to Shore) crane is also included. This has a simple loading
and unloading animation cycle.


===============================================================================

2. INSTALL INSTRUCTIONS

IMPORTANT: READ THE MODEL INFO NOTES BELOW BEFORE INSTALLING TO DETERMINE IF 
YOU NEED OR WANT TO INSTALL ALL 5 SHIPS.

Unzip the ship_5000TEU.zip file into a temporary folder.

Copy or move only the .s and .sd files you want to use into the route SHAPES 
folder.

Copy or move the .ACE files into the route TEXTURES folder.

Copy and paste all of the following into the .ref file for the route.

Static (
   Class ( Ships )
   Filename ( ship_5000teu.s )
   Align ( None )
   Description ( "container ship" )
)


Static (
   Class ( Ships )
   Filename ( ship_5000teu_bow.s )
   Align ( None )
   Description ( "container ship bow pivot" )
)

Static (
   Class ( Ships )
   Filename ( ship_5000teu_stern.s )
   Align ( None )
   Description ( "container ship stern pivot" )
)

Static (
   Class ( Ships )
   Filename ( ship_5000teu_port.s )
   Align ( None )
   Description ( "container ship port pivot" )
)

Static (
   Class ( Ships )
   Filename ( ship_5000teu_stbd.s )
   Align ( None )
   Description ( "container ship starboard pivot" )
)

Static (
   Class ( Ships )
   Filename ( sts_crane.s )
   Align ( None )
   Description ( "container crane" )
)

===============================================================================

3. ACKNOWLEGMENTS and CREDITS

Many Thanks to the following:

To all the tutorial writers and developers of all the MSTS utilities.

All the contributors to MSTS forums who have posted resolutions/findings to 
other peoples problems and letting me stand on the shoulders of giants.

===============================================================================

4. MODEL INFO

This model was built using GMAX.

This is a stand off model and is derived from my bulk ore carrier. The main 
details are there for a (hopefully) fair representation. The superstructure is 
a simplified representation derived from numerous sources and deck details are 
sparse as this area is not normally be seen by landlubbers.

Due to the size of this model and the 2000 metre visual limit of MSTS there 
are 5 versions of this model.

3D models are displayed in MSTS when the player/camera comes within 2000 metres 
of the models 'pivot point'. In most cases this is at the centre of the model. 
The problem with a model of this size is that when the player approaches within 
2000 metres of the pivot point the ship suddenly pops up out of the blue and 
onto the screen, which I find annoying.

My work around is to offset the pivot point away from the centre and towards 
the intended player/camera position by 500 metres. This means there are 5 
copies of the same ship with the pivot points 500 metres to either the normally 
placed centre of the ship as well as the port, starboard, bow and stern of the 
ship.

Now if approaching the ship (with the pivot point at the bow) from the front, 
the bow appears out of the fog/haze. After another 240 metres later the bridge 
appears out of the fog. I find this gradual appearance of the ship far 
preferable to the sudden pop ups that occur when the pivot point is at the 
centre of the ship.

The problem with the method above is that the ship would appear later than 
normally if approached from the opposite direction of the pivot point. As ships
are usually located to one end of a route and at sea this would be a rare 
scenario.

As objects are moved around by their pivot points this can make it a bit more 
difficult to place and move the models around in the Route Editor. As advised 
there is also a ship with its pivot point at the centre of the ship for those 
who prefer the normal settings.

Open Rails can have the default draw distance increase by an option setting so
this will be less of an issue in this simulator.

The Ship to Shore crane also is very basic and has been designed to be viewed 
from a distance. A simple animation of a loading/unloading cycle is included.
If you wish the STS crane to be animated, right click the crane once it has 
been placed in your route and tick the 'Animate this Object' tick box.

===============================================================================

5. TERMS OF USE, DISCLAIMER & LEGAL STUFF

This is an artistic interpretation represented by an electronic image of a 
generic container ship.

All contents of this add-on are Copyright 2013 Marek Lemow. This model is not 
"public domain". This model is distributed as Freeware for personal, 
non-commercial use only. You may not sell all or any part of this package 
without my express written permission.

Any work you derive from the included files is entirely your own. You may do 
as you please with any derrived work from these files. If you wish to release 
your derived work, you do not require my permission, blessing or acknowlegement. 
In short, with any derived work, do as you please.

By downloading and/or using this model, you have agreed with these terms and 
conditions of use.

This download will not break your pc but if it does, it was not anything I did.

If you do not like this model please delete it from your computer.

Any comments, issues or further correspondence may be directed to 
superheatedsteam@yahoo.com
