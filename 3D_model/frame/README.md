# Frames readme or how to choose a frame for the M Prime One

Each M Prime One needs only one frame, but there are several variants of this part that you can choose from. This document helps you choose one of them.

## Content of this directory

This directory contains the Freecad and fabrication (`.dxf`) files for the M Prime One frame. It can be laser cutted or CNCed in a sheet of acrylic, aluminium, etc. The design has been tested with 8mm acrylic.

## Frame variants

Currenty, there are 3 variants of the frame:

* **Default frame** (`frame`). This is the basic frame, the one that appears in the complete 3D model of the printer. It includes a handle.
* **Frame without handle** (`frame_no_handle`). The same as the basic frame, but without the handle so you can save some height centimeters. You can use the same rod lengths as in the basic frame and you'll also obtain the same printing height.
* **A4 frame** (`frame_A4`). A reduced version of the frame that lets you use a laser cutter or CNC with a cutting area the size of an A4. It hasn't been tested yet, and it requires shorter z rods. Printing height is also reduced to only about 60mm.

The characteristics of the frame variants is summarized in the following table:

|      Frame      |     File name     | Printing height | External dimensions |
| --------------- | ----------------- | --------------- | ------------------- |
| Default frame   | `frame`           | 150mm           | 436x170mm           |
| No handle frame | `frame_no_handle` | 150mm           | 385x170mm           |
| A4 frame        | `frame_A4`        | 62mm            | 170x297mm           |

The only tested variant is the default frame and the others should only be chosen by users prepared to make small changes or adjustements.