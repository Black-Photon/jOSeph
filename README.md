# System Operatus

## Overview
Attempt to create a new Operating System based on tutorials from https://wiki.osdev.org

## Dependancies
- Must have the GCC cross-compiler for i686 installed into `..\Programs\i686-elf-tools-windows` (may wish to use provided at https://github.com/lordmilko/i686-elf-tools/releases/tag/7.1.0)
- Requires wsl installed with the following packages:
  - `xorriso`
  - `grub-common`
  - `grub-pc-bin`

## Build instructions
Instructions assume using Windows
1) Then you can build the `.iso` by running `make`
2) Run the OS with Qemu VM using `qemu-system-i386 -cdrom .\build\operatus.iso`