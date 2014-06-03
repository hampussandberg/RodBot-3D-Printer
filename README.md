##RodBot - 3D Printer  

This project started out as a small upgrade to a kit 3D printer I bought but ended up as a complete printer.  

It is designed around a frame of M10 threaded rods for stability, which is where the name come from as well. All plastic parts are printable and are made to be sturdy for stability.  

The weakest link I found in the kit printer I started out with was that many printed parts where mounted together to form a bigger part. I tried to avoid this by making the parts as big as necessary and only mounting hardware like rods and bearing blocks. This will of course mean more material is needed and the total weight of the printed parts is around 900 grams.  

The X-carriage was designed to fit a [Greg's Wade reloaded](http://www.thingiverse.com/thing:18379) or my remix of [Minimalistic Mk7 replacement](http://www.thingiverse.com/thing:251112)  
It's probably possible to use other extruders using the 50 mm hole distance as well.  

Some of the parts needed:  
* M10 threaded rods + nuts and washers  
* M8 threaded rods + nuts and washers  
* M6 threaded rods + nuts and washers  
* 8 mm Smooth rods  
* SC8UU bearing blocks  
* RepRap PCB Heatbed, I'm using [this one](http://reprap.me/heatbed/mk2-231.html)  

**Note:** Some parts might need to be rotated in order to print them.  

The frame blocks are designed to work with this [Heavy duty Vibration damper](http://www.thingiverse.com/thing:94279 )  

I have made a 3D PDF of the printer available for [download](https://github.com/hampussandberg/RodBot-3D-Printer/raw/master/Renderings%20-%20Images/RodBot%20Assembly%20Rev%203.PDF)  

##Updates:  
**2014-05-30:** The Y-axis is now modified to use 8 mm smooth rods so that those are the only rods used for the whole printer and SC8UU are used everywhere. I also modifided the design of the Y-motor mount to be able to print it flat (prints faster) and tried to make it more robust. I recommend printing the Y-motor mount at 100% infill. The new parts are:  
- Y Motor Mount Rev 2  
- Y Smooth Rod Ends - Rev 2.1  
- Y Belt Holder Rev 2  

**2014-05-13:** The Marlin configuration I'm using with the RAMPS controller is available on [Github](https://github.com/hampussandberg/RodBot-Marlin-Ramps). I've also moved old compenent no longer used on the newest version of RodBot to an archive folder [here](https://github.com/hampussandberg/RodBot-3D-Printer/tree/master/Archive).    

**2014-05-12:** Modified the Y ends to have a easier and more robust clamp for the belt. It is now easier to adjust the tension as it's just a matter of turning to screws. This also removes the problem I had with the plastic holding the belt cracking. The new parts are:  
- Y Smooth Rod Ends - Rev 2  
- Y Belt Holder  
Hardware needed:  
- 2 pcs M3x25mm or longer  
- 2 pcs M3x16mm  
- 4 pcs M3 Lock nut  
- 2 pcs M3 nut  
- 8 pcs M3 washer  
Some photos of the assembly: [Photo 1](https://raw.githubusercontent.com/hampussandberg/RodBot/master/Renderings%20-%20Images/Photo%202014-05-12%2023%2004%2008.jpg), [Photo 2](https://raw.githubusercontent.com/hampussandberg/RodBot/master/Renderings%20-%20Images/Photo%202014-05-12%2023%2003%2046.jpg), [Photo 3](https://raw.githubusercontent.com/hampussandberg/RodBot/master/Renderings%20-%20Images/Photo%202014-05-12%2023%2003%2052.jpg).  

**2014-05-08:** All files are available on [GitHub](https://github.com/hampussandberg/RodBot-3D-Printer) along with some development and some old files as well.  

**2014-04-30:** I recently replaced my J-Head hotend with an [E3D hotend](http://e3d-online.com/) but I needed to widen the x assembly by 5 mm in order to fit it. The new parts for the wider x-assembly are:  
- X Carriage Rev 3  
- X-End Idler Clamp Rev 2  
- X-End Idler Rev 2  
- X-End Motor Clamp Rev 2  
- X-End Motor Rev 2  
To secure the E3D Hotend I'm using [this mount from dmarett](http://www.thingiverse.com/thing:220811). See the pictures I've taken for more details.

**2014-03-29:** The fan mount I designed didn't work very well so I have now replaced it with [this](http://www.thingiverse.com/thing:283862), which is a remix of [this one](http://www.thingiverse.com/thing:30721) but with a slightly modified mount to fit on the two screws for the belt holders.

##License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/3.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/">Creative Commons Attribution-ShareAlike 3.0 Unported License</a>.
