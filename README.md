# 1541-Parallel_Adapter
This is an adapter to easier add a parallel port for the Commodore 1541 and 1541-II diskette drive.
You can (and should) read more on Peter's site https://ist.uwaterloo.ca/~schepers/1541par.html

Item list.
* 15CM 10 wire flatcable.
  * or 8 wire flatcable for ZoomFloppy.
* 15pin D-sub female(not the VGA type), either solder or for IDC ribbon cable (last one recommended).
* 40 pins IC socket.
* 2 x 20 pins sil header male-male. (turned/tulip recommended).

All items can be found on eBay or your favorite electronics pusher.

Pin 1 from the PCB connects to Pin 1 of the D-sub connector, 2 to 2 etc.

**Let the PCB be as thin as possible, otherwise you need thicker washers. Testet is a 0.8mm thick adapter. **

Washers is needed for the 1541-II drive to lift the mechanical parts.
1.6mm (2 x 0.8mm) height with an inner diameter of 4mm is sufficient to lift the drive.

Connecting the adapter to ZoomFloppy

For solder pins
![SolderPins](/Pics/forDoc/15Female.jpg)

Adapter | 15pin D-sub female
------------ | -------------
Pin 1 | Pin 1
Pin 2 | Pin 2
Pin 3 | Pin 3
Pin 4 | Pin 4
Pin 5 | Pin 5
Pin 6 | Pin 6
Pin 7 | Pin 7
Pin 8 | Pin 8

Soldering the cable for this is just the same pinout

15pin D-sub male | 15pin D-sub female
------------ | -------------
Pin 1 | Pin 1
Pin 2 | Pin 2
Pin 3 | Pin 3
Pin 4 | Pin 4
Pin 5 | Pin 5
Pin 6 | Pin 6
Pin 7 | Pin 7
Pin 8 | Pin 8




If you choose to use the connector to press the IDC connector and don't want to use a 15 pin cable wasting 7 wires, you can hook it up like this

![SolderPins](/Pics/forDoc/15FemaleIDC.jpg)

Adapter | 15pin D-sub female (IDC)
------------ | -------------
Pin 1 | Pin 1
Pin 2 | Pin 9
Pin 3 | Pin 2
Pin 4 | Pin 10
Pin 5 | Pin 3
Pin 6 | Pin 11
Pin 7 | Pin 4
Pin 8 | Pin 12

The cable should be soldered accordingly

15pin D-sub female | 15pin D-sub male
------------ | -------------
Pin 1 | Pin 1
Pin 2 | Pin 9
Pin 3 | Pin 2
Pin 4 | Pin 10
Pin 5 | Pin 3
Pin 6 | Pin 11
Pin 7 | Pin 4
Pin 8 | Pin 12





Many thanks to [Peter Schepers](https://ist.uwaterloo.ca/~schepers/1541par.html).
