---
layout: default
title: Metal microdrive
parent: Microdrives
nav_order: 1
---
![Recoverable microdrive](https://buzsakilab.github.io/3d_print_designs/images/recoverable_microdrive.jpg)

# Recoverable metal microdrive
{: .no_toc}
Metal microdrive for silicon probe recordings. Below are necessary design files and detailed instructions for assembling the microdrives yourself. You may also order them from our production partner 3Dneuro. 

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Ordering and assemble the drive yourself
The .step files are optimized for stainless steel 316L, 20 micrometer resolution and aluminum AlSi10Mg, high resolution using Proto Labs (https://www.protolabs.com/). Download step files from the [GitGub repository](https://github.com/buzsakilab/3d_print_designs/tree/master/Microdrives/Metal_recoverable).

In order to receive high quality prints from ProtoLabs, please follow these instructions:

1. Add the following note to _drive_v09_: "Use orientation as in quote 9301-742"
2. Add the following note to _arm_v09_aluminum_: "Use orientation as in quote 2379-080"

For other printers, materials or printing companies, modifications may be necessary.

## Purchasing fully assembled microdrives
To purchase fully assembled drives, please contact [3Dneuro](https://www.3dneuro.com/2021/04/23/new-metal-microdrive-in-collaboration-with-the-buzsaki-lab/) (our partner in production).

## Assembly instructions 
See video below. Detailed assembly instructions are available for the [metal microdrive](https://github.com/buzsakilab/3d_print_designs/raw/master/Microdrives/Metal_recoverable/assembly_instructions_implantation_tool_metal_v9.pdf) and for the [implantation tool](https://github.com/buzsakilab/3d_print_designs/raw/master/Microdrives/Metal_recoverable/assembly_instructions_implantation_tool_metal_v9.pdf).

<video width="100%" height="auto" controls="controls">
  <source src="https://buzsakilab.com/3d_print_designs/Figure1-video1.mp4" type="video/mp4">
</video>

The assembly video is also available on [youtube](https://www.youtube.com/watch?v=poEjWvFrr5g). Neuropixels probe attachment (or any other silicon probe) are available [here](https://www.youtube.com/watch?v=MpPdWJEo7Fo).

## Materials

__Metal microdrive v9 (1/2")__ 

| Qty | Name | Vendor | Item number/Link |
|-----|------|--------|-------------|------|
| 4 | 00-90 nut | McMaster | [92736A112](https://www.mcmaster.com/92736a112) |
| 1 | 00-90 screw 1/2" | McMaster | [92482A235](https://www.mcmaster.com/92482a235/) |
| 3 | 00-90 screw 1/4" | McMaster | [93701A005](https://www.mcmaster.com/93701A005/) |
| 1 | 2-56 nylon screw 1/4" | McMaster | [95868A132](https://www.mcmaster.com/95868A132/) |
| 1 | 000-120 screw 1/8" | McMaster | [90910A600](https://www.mcmaster.com/93701a005) |
| 1-3 | male header pin | DigiKey | [SAM1067-40-ND](https://www.digikey.com/products/en?keywords=SAM1067-40-ND) |


__Additional tools__ 

| Qty | Name | Vendor | Item number/Link | Notes |
|-----|------|--------|-------------|-------|------|
| 1 | T2 screwdriver | McMaster | [52995A31](https://www.mcmaster.com/52995a31) |  | 
| 1 | T1 screwdriver | McMaster | [52995A31](https://www.mcmaster.com/52995a31) |  | 
| 1 | 00-90 Tap      | McMaster | [2504A14](https://www.mcmaster.com/2504A14/) | Or similar 00-90 tap. |
| 1 | 000-120 Tap    | McMaster | [2504A12](https://www.mcmaster.com/2504A12/) | Or similar 000-120 tap. |
| 1 | 2-56 Tap       | McMaster | [2522A713](https://www.mcmaster.com/2522A713/) | Or similar 2-56 tap. |
| 1 | Ball-End       | McMaster | [5497A24](https://www.mcmaster.com/5497A24/) |  | 
|   | Hex Screwdriver |  |  |  |  | 
| 1 | 1.2 mm drill bit |  McMaster | [2958A29](https://www.mcmaster.com/2958a29) | Or similar drill bit. | 


## Citations
If you use our designs, please cite our paper: 
Metal microdrive and head cap system for silicon probe recovery in freely moving rodent Mihály Vöröslakos, Peter C. Petersen, Balázs Vöröslakos, György Buzsáki doi: [doi.org/10.1101/2020.12.20.423655](https://doi.org/10.1101/2020.12.20.423655)

The original idea of the drive is described in the following paper:

Micro-drive and headgear for chronic implant and recovery of optoelectronic probes Jinho Chung, Farnaz Sharif, Dajung Jung, Soyoun Kim & Sebastien Royer Scientific Reports, volume 7, Article number: 2773 (2017) [doi:10.1038/s41598-017-03340-5](https://doi.org/10.1038/s41598-017-03340-5)

The designs are distributed under GNU GPLv3 license.