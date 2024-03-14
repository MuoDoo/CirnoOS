# CirnoOS
CirnoOS is an operating system kernel written in Rust.
![](./img/cirno.png)

## Features
* Linux compatible syscall interface: run Linux userspace programs
* Simple File System
* Network stack
* Signal System
* Async I/O
* Display Driver

## Struct
The core part is in `./CirnoCore/`. It includes all parts in core OS.

The user part is in `./CirnoUser/`. It is actually an userlib for this OS. You can add new executable files into this OS in `./CirnorUser/src/bin`.


## Building

### Environment

* Rust toolchain
* QEMU >= 4.1.0

Setup on Linux or macOS

`$ rustup component add rust-src llvm-tools-preview`

### How to run
```bash
git clone https://github.com/MuoDoo/CirnoOS.git
cd CirnoOS/CirnoCore
make run GUI=on
```
## Licence
This source code is under [MIT Licence](LICENSE).