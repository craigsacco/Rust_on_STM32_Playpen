# Environment Setup

## Tools

* OpenOCD 0.11.0
* GNU Tools for ARM Embedded 10.3-2021.10
* STM32CubeProj 2.8.0

## Install additional Rust targets

* For STM32L4xx: ``rustup target add thumbv7em-none-eabihf``

## Install additional Rust tools

* ``cargo install cargo-binutils``
* ``rustup component add llvm-tools-preview``
