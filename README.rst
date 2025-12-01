# QEMU Custom Fork

This repository contains a custom fork of QEMU.  
The goal of this project is to modify how QEMU exposes certain hardware and system information to the guest system for research, testing, and experimentation purposes.

## Project Goals

- Customize identifiers and values exposed by QEMU (CPU information, SMBIOS, BIOS/UEFI data, device descriptors, etc.).
- Modify how various internal structures are reported to the guest.
- Allow experiments related to virtualization detection, compatibility testing, and system behavior analysis.
- Maintain compatibility with standard QEMU features as much as possible.

## Features

- Customizable emulated hardware components.
- Adjusted system identifiers and descriptors.
- Experimental modules for testing alternative system behaviors.
- Mostly compatible with standard QEMU build and runtime workflows.
