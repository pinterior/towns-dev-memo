---
title: FM TOWNS Dev Memo
---

## Operating Systems

### Preparation

- [CMOS (NVRAM)](./etc/cmos.md)

### Installation

- [MS-DOS 6](./os/dos6.md)
- [TownsOS V2.1 on MS-DOS 6](./os/tos-dos6.md)

## Toolchains

### MS-DOS Target

to build `.exe` files.

#### Native

- C
   - LSI C-86
- Assembly
   - MASM

#### Cross

- C/C++
   - Visual C++ 1.51
- Assembly
   - MASM

### 386|DOS-Extender Target

to build `.exp` files.

#### Native

- C
   - [High C 1.7](./langs/highc17.md)
- Assembly
   - 386|ASM

#### Cross
