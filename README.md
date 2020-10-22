# Introduction

Welcome to the Universal Payload project. The goal of this project is to define an interface between a first stage platform initialization bootloader and a second stage payload.

## Specification
 
The interface specification is at 
https://universalpayload.github.io/documentation/spec/spec.html

The specification source is maintained in restructured text format and is available at 
https://github.com/universalpayload/documentation

## Sandboxes

A few example implementations of the Universal Payload specification are available.

### Slim Bootloader

An POC implementation of Slim Bootloader conforming to the Universal Payload specification
https://github.com/universalpayload/slimbootloader/tree/universal_payload

### coreboot

An POC implementation of coreboot conforming to the Universal Payload specification
https://github.com/universalpayload/coreboot/tree/universal_payload

### UEFI Payload

An POC implementation of UEFI Payload conforming to universal payload specification.
https://github.com/universalpayload/edk2/tree/universal_payload

### Linux Payload

An POC implementation of Linux Payload containing necessary patches to build a basic Linux payload conforming to the universal payload specification.
https://github.com/universalpayload/linuxpayload

### Tools

The pack_payload.py tool can be used to pack a normal payload image into the universal payload image format
The clone_and_build_sbl_with_uefipayload.py tool could clone and build SBL + UEFI payload to have a quick try.
https://github.com/universalpayload/tools
