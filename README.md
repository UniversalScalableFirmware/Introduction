# Introduction

Welcome to the Universal Scalable Firmware project. The goal of the Universal Scalable Firmware project is to evolve the goodness of modularity to scale for IP FW development model, with emphasis on simplicity, scalability, debuggability, readability and determinism.

An **overview** of Universal Scalable Firmware project can be read here https://github.com/UniversalScalableFirmware/Introduction/blob/main/USF_Overview.pdf

## Specification
 
The interface specification is at 
https://universalscalablefirmware.github.io/documentation/

The specification source is maintained in restructured text format and is available at 
https://github.com/UniversalScalableFirmware/documentation

## Sandboxes

Some sandbox implementations done as proof of concept of the Universal Scalable Firmware specification are available.

### Slim Bootloader

An POC implementation of Slim Bootloader 
https://github.com/UniversalScalableFirmware/slimbootloader

### coreboot

An POC implementation of coreboot 
https://github.com/UniversalScalableFirmware/coreboot

### UEFI Payload

An POC implementation of UEFI Payload 
https://github.com/UniversalScalableFirmware/upld_test

### Linux Payload

An POC implementation of Linux Payload containing necessary patches to build a basic Linux payload
https://github.com/UniversalScalableFirmware/linuxpayload

### Tools

The pack_payload.py tool can be used to pack a normal payload image into the universal payload image format
The clone_and_build_sbl_with_uefipayload.py tool could clone and build SBL + UEFI payload to have a quick try.
https://github.com/UniversalScalableFirmware/tools

### Training

USF Training Videos can be viewed https://www.youtube.com/watch?v=OBU7kIdbUY0&list=PLehYIRQs6PR5N73cbW8CPvU_stDTAG_j5
USF Training PDFs https://github.com/UniversalScalableFirmware/Introduction/USF_Training