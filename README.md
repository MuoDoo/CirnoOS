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

## Cirno
>  "Like I care! I'm the fairy who shall soon lord over Gensokyo! I can go anywhere and do anything I want!" &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
>
> <sup>—— Cirno <sup>(Hidden Star in Four Seasons Stage 2.)</sup></sup> 

[Cirno](https://en.touhouwiki.net/wiki/Cirno) is a popular character in Touhou Project.She is an ice fairy who first appeared on the second stage of Embodiment of Scarlet Devil. In comparison to other fairies, she is relatively strong; however, compared to the vast majority of Gensokyo's residents, her strength is subpar. She displays traits on par with that of a child, and stars as the main protagonist of Great Fairy Wars, and one of several protagonists in Touhou Hisoutensoku and Hidden Star in Four Seasons.

## Licence
This source code is under [MIT Licence](LICENSE).