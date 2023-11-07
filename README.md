# 3D-Printer-PS
Contains all design files related to the PS 3D printer.

## Introduction
A 3D printer was always on my list of tools I want but do not need (what was I wrong). In the fall of 2022, I bought two second-hand M3D mini printers with outdated firmware and software and I was sold. However, the M3D printer has its limitations and without hesitation I thought how hard could it be to build my own printer. I started with some research, a BTT SKR mini V3 and my M3D printer and started with the build of my own 3D printer. After designing and printing (in PLA) the first coreXY layout I knew that this was my new hobby. 
I have a background in embedded systems and want to learn the methods of designing mechanical hardware. The printer is inspired by multiple open-source printers and professional FDM printers. 

## Design
Frame:
- 440mmx440mmx500mm 
Goal is to fit everything with this frame

Kinametics:
- X, Y = CoreXY based on linear rods
- Z = Two linear screws. Next update will be three separate Z axis.

Toolhead: 
I designed and used three versions of my own toolhead. Unfortunately each had its own flaws. For now stick to the Voron stealthburner.
- Voron Stealthburner with custom interface to CoreXY

Electronics
- BTT SKR mini V3
- BTT EBB SB
