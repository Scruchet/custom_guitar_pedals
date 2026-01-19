# Custom Guitar Pedals

## Introduction
Since I started learning how to play the electric bass and guitar, and while learning new songs, I discovered effect pedals. They change the sound of the instrument by adding more texture and character. Many different types of pedals exist, and I wanted to understand how they work.

My research is mainly based on a book that I highly recommend: *Electronics for Guitarists* (third edition).

## Project Structure
This repository contains all the files needed to create your own guitar pedals, from electronic design to 3D models and circuit simulation.

The main directory is divided into three subdirectories:
- **mechanical**: Fusion 360 and STEP files for the enclosure
- **pcb**: KiCad projects with an HTML-generated BOM for easier assembly
- **simulation**: LTSpice projects used to design and validate the two main circuits

## Effects
The project currently includes two pedals:
- A clipping pedal
- A fuzz face–style pedal

## Assembly
To assemble the pedals, you will need several components. All passive and active components are listed in the BOM available at `pcb/bom/ibom.html`.

You can 3D print the enclosure, but I do not really recommend it. A pedal needs to be solid and reliable, especially for stage use.  
I bought aluminum enclosures from AliExpress and adapted the designs to fit the available space. The quality is not the best, but this is a DIY project after all.

You will need:
- Two 6.35 mm jack connectors (input and output)
- One DC jack for the power supply
- One LED with its current-limiting resistor
- One 3PDT guitar footswitch

All the components I used are listed in the `components.txt` file.

## Results

`images/result.jpg`

## Project Status

Tested, need pictures for the readme

## License
All hardware designs, schematics, PCB layouts, and mechanical files in this repository
are released under the CERN Open Hardware Licence v2 – Permissive (CERN-OHL-P).




