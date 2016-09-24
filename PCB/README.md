# PCB Files

This director contains all the files needed to modify the design of the DMX-Card. Revisions are separated into sub-directories, each of which contain the following files:

* Eagle `.BRD` and `.SCH` files (generated in Eagle 7.6.0)
* Board and schematic `.PNG` files for ease-of-access
* Gerber files
* Bill of Materials

Please note the following:
* All Eagle files have been checked for ERC and DRC errors using rule files provided by Elecrow. **If you choose to use a different fab house, please ensure that the boards meet their DRC requirements.**
* Similarly, the Gerber files have been generated using a CAM file provided by Elecrow; if you are planning to utilize a different fab house, you should either check to ensure they can accept the Gerber files located in this repository or generate your own Gerber files from the Eagle board and schematic files.

## Versions
### Version 1.1
Resolved several issues with version 1.0:
* Mounting holes in V1.0 were placed close to the edge of the board, which resulted in a high probability of edge breakage when depanelizing the boards. As a result, mounting holes have been reworked for greater clearance; note that some holes may be inaccessible depending on the connector choice.
* Input header moved away from the edge of the board to improve screw terminal block support.
* Electrolytic capacitor footprint removed; it was initially included in case additional decoupling was needed, but after testing the existing decoupling is satisfactory.
* Improved SMD component placement for easier hand-soldering. Namely, the two 10uF decoupling capacitors on the isolated side have been spaced further apart from each other, and the SM712 diode has been moved away from R9.
* Improved silkscreen layout to avoid conflicts with pads and vias.

### Version 1.0
Initial release. This version has been tested and is proven to work as described.

