# PCB Files

This director contains all the files needed to modify the design of the DMX-Card. Revisions are separated into sub-directories, each of which contain the following files:

* Eagle `.BRD` and `.SCH` files (generated in Eagle 7.4.0
* Board and schematic `.PNG` files for ease-of-access
* Gerber files
* Bill of Materials

Please note the following:
* All Eagle files have been checked for ERC and DRC errors using rule files provided by Elecrow. **If you choose to use a different fab house, please ensure that the boards meet their DRC requirements.**
* Similarly, the Gerber files have been generated using a CAM file provided by Elecrow; if you are planning to utilize a different fab house, you should either check to ensure they can accept the Gerber files located in this repository or generate your own Gerber files from the Eagle board and schematic files.
