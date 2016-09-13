# DMX-Card

## Description:
The DMX-Card is a small breakout board that allows developers to quickly add a UART-to-DMX (RS-485) circuit to their designs. It has been designed to cut down on the time spent constructing isolated DMX-512 circuits for prototype designs. The circuit is fully isolated and protected against ESD, and can be easily configured with a 3-pin XLR, 5-pin XLR, or 0.100" connector of the user's choice.

## Features:
* +5V input with polarity and over-current protection
* Isolated input and output:
  * Isolated DC-DC converter (1.5kVDC)
  * Isolated I/O via optocoupler (2.5kVDC)
  * ESD protection on all data inputs and outputs (including DMX)
* Full DMX compliance*
  * ANSI E1.20-2006 RDM compliant circuit, including correct biasing resistors (562/130/562)
  * 10MBd optocouplers
* User-selectable output connectors:
  * Neutrik NC3FAH (3-pin XLR)
  * Neutrik NC5FAH (5-pin XLR)
  * 0.100" PTH connectors (headers, screw terminal blocks, etc.)

## Physical:
* Dimensions: 0.95" x 1.90" (24.13mm x 48.26mm)
* Board Thickness: 1.6mm
* Input Power: +5VDC, 450mA max**
* Input Connections: +5V, GND, RX, TX, RX/TX Select
* Output: Isolated RS-485/DMX-512 (GND-ISO, D-, D+)
* Mounting: 4x 0.125" holes, located at edges of board

**circuit is constructed to ANSI E1.20; RDM must be correctly implemented on controller for full compliance*

***some specifications subject to change and final testing*
