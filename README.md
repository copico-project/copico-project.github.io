# CoPiCo Project

<p align="center">
  <img width="360" src="https://github.com/copico-project/copico-project.github.io/assets/12594889/726c1f5f-8639-4f95-b4bc-d80b4835354b" alt="CoPiCo logo">
</p>

## What is the CoPiCo?

The CoPiCo is a cartridge for the Tandy Color Computer that adds WiFi to and serves as a boot ROM for the system.

It is built around the official dev board for the RP2040 microcontroller, the Raspberry Pi Pico W, which includes onboard WiFi.

## Site still under construction!

This site is a work in progress. It will soon contain documentation and project updates.

## WiFi Connectivity

The firmware (see 'copico-firmware' repo) will behave more like a SPI WiFi
module or the WizNet chip (or perhaps both, depending on mode). It will, of
course, also allow listing and connecting to the desired WiFi network.

## ROM Emulation

CoPiCo will also support boot ROM emulation (initially just for a 1 KB ROM due
to limitations of first revision of the CoPiCo PCB). Henry Strickland
(@strickyak) plans to use this feature to load a version of his
"axiom" network boot ROM (see
https://github.com/strickyak/frobio/tree/main/frob3/booting).

## Other Future Capabilities

Future capabilities for the CoPiCo may include:
- VGA or HDMI output based on the captured contents of video RAM
- Logic capture / bus trace
- Remote debug, with breakpoints and watchpoints

## Signage from Unveiling at the Vintage Computer Festival SoCal

Until we get a chance to create a better site, here's a look at the board and our booth signage from the grand unveiling of the project at VCF SoCal!

![slide](https://github.com/copico-project/copico-project.github.io/assets/12594889/9eda657b-8d8f-4d80-92b9-797193df81df)

![copico_pcb_rev0 1_front](https://github.com/copico-project/copico-project.github.io/assets/12594889/0aa3bfe4-2129-4f73-a520-9b2466cd4f9c)

![copico_pcb_rev0 1_back](https://github.com/copico-project/copico-project.github.io/assets/12594889/a098ccb4-ed93-4c8d-b08d-daa03b462ec4)

![copico_rev0 1_schematic](https://github.com/copico-project/copico-project.github.io/assets/12594889/c0cf58be-9429-46f0-86e5-202292c2e352)

## GitHub Respositories

You can find the KiCad source for the board and the source code for the microcontroller firmware in the following repos:
- [github.com/thomasshanks/copico-board](https://github.com/thomasshanks/copico-board)
- [github.com/thomasshanks/copico-firmware](https://github.com/thomasshanks/copico-firmware)

## Stay Tuned to This Channel

Please watch this space for updates as development continues!

Thank you for being a part of the Retrocomputing community!


Thomas Shanks (copico@tshanks.org)    
18 Feb 2024
