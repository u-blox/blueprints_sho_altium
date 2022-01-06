# u-blox Blueprints

Design files and source code for blueprints/reference designs
================================================================================

The designs contained within this repository are u-blox blueprints. These are
example designs suitable for a starting point in an end-product. These are
not full EVKs, rather an example of a feature or used in a project.

The following blueprints are maintained here:

|Blueprint number | Description                                                    |
|-----------------|----------------------------------------------------------------|
| B212            | RF range test board, 40x22 plane, ANNA-B112 in corner position |
| B213            | RF range test board, 22x20 plane, ANNA-B112 in corner position |
| B214            | RF range test board, 40x22 plane, ANNA-B112 in edge position   |
| B215            | RF range test board, 22x20 plane, ANNA-B112 in edge position   |
| B216            | RF range test board, 40x22 plane, BMD-300, BMD-330, or BMD-360 |
| B217            | RF range test board, 22x20 plane, BMD-300, BMD-330, or BMD-360 |
| B218            | RF range test board, 40x22 plane, BMD-340                      |
| B219            | RF range test board, 22x20 plane, BMD-340                      |
| B220            | RF range test board, 40x22 plane, BMD-350                      |
| B221            | RF range test board, 22x20 plane, BMD-350                      |
| B222            | RF range test board, 40x22 plane, BMD-380                      |
| B223            | RF range test board, 22x20 plane, BMD-380                      |
| B224            | RF range test board, 40x22 plane, NINA-B112                    |
| B225            | RF range test board, 22x20 plane, NINA-B112                    |
| B226            | RF range test board, 40x22 plane, NINA-B302                    |
| B227            | RF range test board, 22x20 plane, NINA-B302                    |
| B228            | RF range test board, 40x22 plane, NINA-B306                    |
| B229            | RF range test board, 22x20 plane, NINA-B306                    |
| B230            | RF range test board, 40x22 plane, NINA-B406                    |
| B231            | RF range test board, 22x20 plane, NINA-B406                    |
| B232            | RF range test board, 40x22 plane, NORA-B106                    |
| B233            | RF range test board, 22x20 plane, NORA-B106                    |

Directory structure
---------------------------------------------------------------------------------
```
/--+---Designs (Altium design files)
   |   |
   |   +--- Bxxx
   |   +--- Byyy
   |   +--- Bzzz
   |   ...
   |
   +---Chamber scans
       |
       +--- Bxxx
       +--- Byyy
       +--- Bzzz
       ...
```

Chamber scans
---------------------------------------------------------------------------------
If an RF chamber scan exists for the blueprint, it can be found in this folder.
The chamber scan folders contain four matching HTML files and folders. To see the
2D and 3D chamber scans, open the respective HTML file with a browser. 

The 2D file shows separate plots for horizontal, vertical, and combined readings
for the X-Y, X-Z, and Y-Z planes. 

The three 3D files all show the same three-dimensional plot, except the initial
view is of the selected plane, X-Y, X-Z, or Y-Z. The three plots can be zoomed
and rotated by clicking and dragging the mouse cursor.

---------------------------------------------------------------------------------
Copyright © u-blox

u-blox reserves all rights in this deliverable (documentation, software, etc.,
hereafter “Deliverable”).

u-blox grants you the right to use, copy, modify and distribute the Deliverable
provided hereunder for any purpose without fee.

THIS DELIVERABLE IS BEING PROVIDED "AS IS", WITHOUT ANY EXPRESS OR IMPLIED
WARRANTY. IN PARTICULAR, NEITHER THE AUTHOR NOR U-BLOX MAKES ANY REPRESENTATION
OR WARRANTY OF ANY KIND CONCERNING THE MERCHANTABILITY OF THIS DELIVERABLE
OR ITS FITNESS FOR ANY PARTICULAR PURPOSE.

In case you provide us a feedback or make a contribution in the form of a
further development of the Deliverable (“Contribution”), u-blox will have the
same rights as granted to you, namely to use, copy, modify and distribute the
Contribution provided to us for any purpose without fee.

-------------------------------------------------------------------------------
