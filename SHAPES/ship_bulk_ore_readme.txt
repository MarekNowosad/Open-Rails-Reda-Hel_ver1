Freelance Bulk Ore Carrier 
for Microsoft Train Simulator

February 2006

Original Freeware Model by Marek Lemow (Copyright 2006)


====================================================================================
1. HISTORY
2. INSTALL INSTRUCTIONS
3. ACKNOWLEGMENTS
4. MODEL INFO
5. TERMS OF USE, DISCLAIMER & LEGAL STUFF
====================================================================================

1. HISTORY
 
This is a freelance representation of a bulk ore carrier commonly used to transport bulk cargos like coal, wheat and iron ore around the globe.

Typical specifications for a ship that this model is based on are:

Length:            280m

Beam:              45m

Max draught:       18.5m displacing 170,000 metric tonnes

Fuel consumption:  58 tons of heavy fuel oil per day at economic service speed of 14.7knots

Range:             24,000 nautical miles 

Main Engine:   

1 x 6 cylinder marine diesel engine, turbo charged with Max continuos rating of 15,397kW (20940 bhp) at 88 rpm driving a single 4 bladed 8.1m propeller. 

====================================================================================

2. INSTALL INSTRUCTIONS

IMPORTANT: READ THE MODEL INFO NOTES BELOW BEFORE INSTALLING TO DETERMINE IF YOU NEED OR WANT TO INSTALL ALL 5 SHIPS.

Unzip the ship_obo.zip file into a temporary folder. 

Copy or move only the .s and .sd files you want to use into the route SHAPES folder.

Copy or move all the .ACE files into the route TEXTURES folder.

Using a unicode text editor copy and paste all of the following into the .ref file for the route only if your are adding all 5 ships to your route. If you are not installing all of them then only add the appropriate references.  

Static (
   Class ( Ship )
   Filename ( ship_bulk_ore.s )
   Align ( None )
   Description ( "bulk ore" )
)

Static (
   Class ( Ship )
   Filename ( ship_bulk_ore_bow.s )
   Align ( None )
   Description ( "bulk ore bow pivot" )
)

Static (
   Class ( Ship )
   Filename ( ship_bulk_ore_strn.s )
   Align ( None )
   Description ( "bulk ore stern pivot" )
)

Static (
   Class ( Ship )
   Filename ( ship_bulk_ore_port.s )
   Align ( None )
   Description ( "bulk ore port pivot" )
)

Static (
   Class ( Ship )
   Filename ( ship_bulk_ore_stbd.s )
   Align ( None )
   Description ( "bulk ore starboard pivot" )
)

====================================================================================

3. ACKNOWLEGMENTS and CREDITS

Many Thanks to the following:

Stew Winston for testing, feedback and patience.

To all the tutorial writers and developers of all the MSTS utilities.

All the contributors to MSTS forums who have posted resolutions/findings to their/other peoples problems and letting me stand on the shoulders of giants.

====================================================================================

4. MODEL INFO

This model was built using GMAX and textures with Photoshop 5.5.

This is not a highly detailed model comprising just over 1,000 polygons. It was intended as a stand off model, which is to be located off in the distance, but the main details are there for a (hopefully) fair representation. The superstructure is a simplified representation derived from numerous sources and deck details are sparse as this area is not normally be seen by landlubbers. No prop either as this is normally below the surface of the water.

Due to the size of this model and the 2000 metre visual limit of MSTS there are 5 versions of this model. 

3D models are displayed in MSTS when the player/camera comes within 2000 metres of the models 'pivot point'. In most cases this is at the centre of the model. The problem with a model of this size is that its 280 metres long and 54 metres high. When the player approaches within 2000 metres of the pivot point the entire ship suddenly pops up out of the blue and onto the screen, which I find annoying.

My work around is to offset the pivot point away from the centre and towards the intended player/camera position by 500 metres. This means there are 5 copies of the same ship with the pivot points 500 metres to the port, starboard, bow and stern of the ship as well as one normally placed at the centre of the ship. 

Now if approaching the ship (with the pivot point at the bow) from the front, the bow appears out of the fog/haze. After another 240 metres later the bridge appears out of the fog. I find this gradual appearance of the ship far preferable to the sudden pop ups that occur when the pivot point is at the centre of the ship.

The problem with the method above is that the ship would appear later than normally if approached from the opposite direction of the pivot point. As ships are usually located to one end of a route and at sea this would be a rare scenario. 

As objects are translated and rotated around by their pivot points this can make it a bit more difficult to place and move the models around in the Route Editor. As advised there is also a ship (ship_bulk_ore.s) with its pivot point at the centre of the ship for those who prefer the normal settings.

MSTS ship builder extrodinaire 'Captain Bazza' has suggested using forced perspective for ships at sea. Using Shape File Manager you can scale the ship to a smaller size. If placed correctly in your route (with no normal sized objects close to it) this can give the impression that the ship is further away than it actually is. SFM scaling will not work correctly with the offset pivot point models. Experiment for best results.

====================================================================================

5. TERMS OF USE, DISCLAIMER & LEGAL STUFF

This is an artistic interpretation represented by an electronic image of a generic bulk ore carrier for use only as an add-on enhancement to MSTS or TMTS.

All contents of this add-on are Copyright 2006 by Marek Lemow. All Rights Reserved and subject to change at a whim. This model is not "public domain". This model is distributed as Freeware subject to the following conditions:

This model is for personal and/or non-commercial use only. 

You may not sell or make any money from any part of this package without my express written permission. 

The inclusion of any individual file or files from this archive into another archive (excluding a MSTS or TMTS Freeware route) without the prior permission of the author is prohibited.

You may redistribute all or parts of this archive with a route only if that route is released as freeware. 

If you have poor eyesight and still wish to distribute these models in a payware route then email me to discuss. I charge by the tonne but will throw in a helicopter and a sailor to sweeten the deal.

You may repaint the textures for this model as you desire. 

By downloading and/or using this model, you have agreed with these terms and conditions of use.

This download will not break your pc but if it does, it was something you did, not anything I did.

If you do not like this model please delete it from your computer and free up some disk space.

Any comments, issues, clarifications or further correspondence may be directed to superheatedsteam_at_yahoo.com