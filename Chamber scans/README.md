# EVK and blueprint - RF chamber scans

RF chamber scans are performed selected bluprint designs and EVKs. Blueprints
B212 through B233 correspond to "mid-size" (40 x 22 mm ground plane) and "small-
size" (22 x 20 mm ground plane) carrier boards for the module noted in the
filename and table below. In addition to the two blueprints for each module, 
EVKs were also scanned:

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
| EVK-ANNA-B112C  | ANNA-B112 EVK, SIP placed in the corner of the PCB             |
| EVK-ANNA-B112E  | ANNA-B112 EVK, SIP placed along the PCB edge                   |
| EVK-ANNA-B112U  | ANNA-B112 EVK, external 3.2 dBi whip antenna                   |
| EVK-BMD-300-EVAL| BMD-300 EVK, PCB trace antenna                                 |
| EVK-BMD-301-EVAL| BMD-301 EVK, external 5 dBi whip antenna                       |
| EVK-BMD-330-EVAL| BMD-330 EVK, PCB trace antenna                                 |
| EVK-BMD-340-EVAL| BMD-340 EVK, PCB trace antenna                                 |
| EVK-BMD-341-EVAL| BMD-341 EVK, external 3 dBi whip antenna                       |
| EVK-BMD-345-EVAL| BMD-345 EVK, external 3 dBi whip antenna                       |
| EVK-BMD-350-EVAL| BMD-350 EVK, PCB chip antenna                                  |
| EVK-BMD-360-EVAL| BMD-360 EVK, PCB trace antenna                                 |
| EVK-BMD-380-EVAL| BMD-380 EVK, PCB chip antenna                                  | 
| EVK-NINA-B111   | NINA-B111, external 3.2 dBi whip antenna                       |
| EVK-NINA-B112   | NINA-B112, PIFA antenna                                        |
| EVK-NINA-B301   | NINA-B301, external 3.2 dBi whip antenna                       |
| EVK-NINA-B302   | NINA-B302, PIFA antenna                                        |
| EVK-NINA-B306   | NINA-B306, PCB trace antenna                                   |
| EVK-NINA-B400   | NINA-B400, external 3.2 dBi whip antenna                       |
| EVK-NINA-B406   | NINA-B406, PCB trace antenna                                   |
| EVK-NORA-B106   | NORA-B106, PCB trace antenna                                   |

Unzip the selected file to a folder. 
Each folder contains four files and four similarly named sub-folders:
<board>-2d.html and <board>-2d-files folder
<board>-3d-xy.html and <board>-3d-xy-files folder
<board>-3d-xz.html and <board>-3d-xz-files folder
<board>-3d-yz.html and <board>-3d-yz-files folder

Open the HTML file in a web browser to view the plot.

The three 3D plots display the same data. The only difference is the initial 
view according to the plane in the filename. For example, <board>-3d-xy.html
shows the plot looking at the X-Y plane with the Z-axis "out of the page".
Hovering over a point on the 3D plot will show the measured EIRP, azimuth,
and elevation. Click and drag the plot to rotate it.

The 2D plots display slices of the 3D plot at the X-Y, X-Z, and Y-Z planes.
Hovering over the plot will show the EIRP, angle, and an indication of 
whether the horizontal or vertical antenna axis was used, or a combined 
measurement of the two.

Scans for all blueprints are in 15 degree azimuth and elevation increments. 
Additional scans for EVK-NINA-B302, EVK-NINA-B306, EVK-NINA-B406, 
EVK-BMD-340-EVAL, and EVK-BMD-380-EVAL, denoted by "-5deg" added to the filename

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

---------------------------------------------------------------------------------
