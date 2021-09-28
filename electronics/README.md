# electronic production

## machining (milling) vs. etching boards
- etching is a chemical process
- machining is a mechanical process

## milling machines
- Roland SRM20
- Bantam Tools

## endmills
- dull
  - 25 boards
  - edges are not clean; edges are rough
  - don't break them: expensive, and can be hazardous when they are large

## PCB materials
- rigid
  - FR4 -> DO NOT USE (has glass fiber reinforcement)
  - FR1: brownish color with natural fiber reinforcement
  - Garolite
    - resin with natural composite
- flexible
  - kaptop
  - 3M electrical tape + electrical conducting copper #1126
- high-frequency
  - teflon
  - glass
- copper conversion
  - 0.5oz = 17.5 um

## mods
- convert PCB design to milling instructions
  - mods can convert to Gerber
- board houses
  - **OSHPark**: domestic (USA) board house
  - **JLCPCB**: aggressive chinese board house

## PCB design rules
- 1/64 bit
- 15, 5 mil
- making vias
  - use 0Ohm resistor to jump over small crosses

## components
- using **surface-mount** components
- ATSAMD11C
- ATTINY44A

## types of solder
- lead-free
  - higher melting temperature makes it slightly harder to use
- low-temp
  - used for special cases where board cannot be heated up
  - expensive and less structurally sound

## kinds of soldering
- drag soldering
- wave soldering
- manual soldering

## stuffing process
- work from bottom to top, and inside to outside (not big to small)

## desoldering
- can desolder with a hot air gun
- the solder braid often needs to be primed with molten solder before it sucks solder away
- soldering has flux in it

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
- [mods](https://mods.cba.mit.edu)

## parts of the board
- filter capacity
- voltage regulator
- PNG resolution
  - 1000 dpi -> 1 pixel = 1 mil

## CMSIS-DAP
- CMSIS. Common Microcontroller Software Interface Standard 
- DAP. Debug Access Port
