# electronic production

## stuffing process
- work from bottom to top, and inside to outside (not big to small)

## desoldering
- can desolder with a hot air gun

## prototyping
- cutting traces and soldering jumper wires

## encapsulation
- making the board more robust

## CAM
- original format: Gerber
- 1/1000th of an inch
- 500-1000 dpi ~ resolution of machine
- FlatCAM; software for CAMing PCBs
- G-code: (mods program) mill 2D PCB png
  - four passes for enough copper removed
- files to mill
  - one file (PNG) for milling traces
  - one file (PNG) for milling the exterior of the board (milling the board)

## programming boards
- ISP (older generation)
- UPDI (AVR 0,1-series)
  - much cheaper
- JTAG (ARM)
  - more expensive, but more powerful range

## todo
- [FlatCAM](http://flatcam.org/)
- mods

