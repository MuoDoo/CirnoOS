# CirnoOS
CirnoOS is an operating system kernel written in Rust.
![](./img/cirno.png)

## Features
* Address Space
* Virtual Address
* Process
* File System
* I/O redirect
* Thread
* Virtio Device Driver
* Display Driver

## Struct
The core part is in `./CirnoCore/`. It includes all parts in core OS.

The user part is in `./CirnoUser/`. It is actually an userlib for this OS. You can add new executable files into this OS in `./CirnorUser/src/bin`.


## Requerments
`This part is still working in progress.`

## Usage
In `./CirnoCore/` run command `make run GUI=on(optional)` to make it run in qemu.
