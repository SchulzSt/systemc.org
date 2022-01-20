# SystemC Libraries & Projects

This page gives an overview of open-source SystemC libraries and projects.
Please [let us know][1] if a project or library is missing or needs update.

## Models

This is a list of SystemC models for use in virtual platforms:

| Name             | Description                                                                             | License                                      |
| :--------------- | :-------------------------------------------------------------------------------------- | :------------------------------------------- |
| [NVIDIA Deep Learning Accelerator (NVDLA)][2] | SystemC TLM2.0-compatible virtual platform                 | NVIDIA Open NVDLA License and Agreement v1.0 |
| [ParaNut Processor][24] | Customizable, highly scalable, and RISC-V compatible processor architecture for FPGA-based systems | BSD-2-Clause
| [Virtual Components Modeling Library (VCML) Models][3] | The VCML productivity library contains many component models (ARM, RISC-V, Virtio, ...) | Apache-2.0                                   |
| [Virtual Components Modeling Library (VCML) NVDLA Model][4]  | VCML integration of the NVDLA model                                                     | Apache-2.0                                   |
| [VPV-Peripherals][12]    | Library of example SystemC/TLM peripherals for various SoCs based on the SCC library    | Apache-2.0                                   |

## Productivity Libraries

Productivity libraries contain common resources and building blocks that can be used for High-Level Synthesis or the creation of SystemC-based virtual platforms. 

| Name                         | Description                                                                            | License                      |
|:---------------------------- | :------------------------------------------------------------------------------------- | :--------------------------- |
| [High-Level Synthesis Libs (HLSLibs)][13] | Repository for the unlimited length integer and fixed-point AC types usable with SystemC, plus math, DSP and ML building blocks, as well as SystemC MatchLib | Apache-2.0 |
| [SystemC-Components (SCC)][5] | A light weight productivity library for SystemC and TLM 2.0 based modeling tasks using C++11 provides common functions, components and modules often needed in SystemC based models | Apache-2.0 |
| [Virtual Components Modeling Library (VCML)][6]  | Sockets, Tracing, Registers, GDB server, Logging, Session Protocol, Component Models, Network backends, TLM2.0 protocols | Apache-2.0 |

## Virtual Platforms

This is a list of open-source Virtual Platforms (VPs):

| Name            | Description                              | Workloads                                  | License      |
| :-------------- | :--------------------------------------- | :----------------------------------------- | :----------- |
| [ARMv8 Virtual Platform (AVP64)][7]      | OCX QEMU-based ARMv8 multi-core VP       | CoreMark, Dhrystone, Linux, Xen hypervisor | MIT          |
| [GreenSocs A53 VP][17] | ARM Cortex A53 multi-core VP (registration required) | Linux | GPLv2 |
| [GreenSocs N1 VP][18] | ARM Neoverse N1 multi-core VP (registration required) | Linux | GPLv2 |
| [GreenSocs RISC-V64 VP][19] | 64-bit RISC-V multi-core VP (registration required) | Linux | GPLv2 |
| [HIFIVE1-VP][8] | DBT-RISE-based RISC-V VP                 | FreeRTOS                                   | BSD-3-Clause |
| [OpenRISC 1000 Multicore VP (OR1KMVP)][9]    | OR1KISS-based multi-core OpenRISC1000 VP | Linux                                      | Apache-2.0   |
| [TGC-VP][10]    | The Scale4Edge ecosystem RISC-V VP | FreeRTOS | Apache-2.0 |
| [Xilinx Zynq-7000][16] | QEMU based Xilinx Zynq-7000 SoC connected SystemC TLM 2.0  |  | MIT |



## Compilers and source-to-source transformations 

| Name       | Description                                                                                                              | License    |
| :--------- | :----------------------------------------------------------------------------------------------------------------------- | :--------- |
| [Recoding Infrastructure for SystemC (RISC)][20] | Framework for analysis and agressive parallel simulation of embedded system models described in SystemC | BSD-3-Clause |
| [SystemC compiler][14] | Compiler which translates synthesizable SystemC design to synthesizable SystemVerilog design | Apache-2.0 |
| [Verilator][15] | Compiler and simulator which translates Verilog/SystemVerilog to SystemC | LGPL-3.0  |

## Simulators

| Name          | Description                               | License |
| :------------ | :---------------------------------------- | :------ |
| [SystemC][50] | SystemC 2.3.3 Reference Implementation | Apache-2.0 |
| [SystemC-AMS][51] | SystemC-AMS 2.3 Proof-of-concept implementation | Apache-2.0 |

## Python Integration

| Name       | Description                                                                                                              | License    |
| :--------- | :----------------------------------------------------------------------------------------------------------------------- | :--------- |
| [PySysC][11] | A Python package to make SystemC usable from Python. It supports composition of a SystemC/TLM model as well as running the simulation. | Apache-2.0 |

## Verification 

| Name       | Description                                                                                                              | License    |
| :--------- | :----------------------------------------------------------------------------------------------------------------------- | :--------- |
| [UVM-Connect][23] | UVM-based library that provides TLM1 and TLM2 connectivity and object passing between SystemC and SystemVerilog UVM models and components | Apache-2.0 |
| [UVM-ML][22] | Universal Verification Methodology Multi-Language (UVM-ML) Open Architecture supporting UVM-SV, UVM-e, and UVM-SC | Apache-2.0 |
| [UVM-SystemC][21] | Accellera implementation and standard of the Universal Verification Methodology (UVM) in SystemC | Apache-2.0 |


[1]: https://github.com/accellera-official/systemc.org/issues
[2]: https://github.com/nvdla/vp
[3]: https://github.com/janweinstock/vcml/tree/master/src/vcml/models
[4]: https://github.com/aut0/vcml-nvdla
[5]: https://github.com/Minres/SystemC-Components
[6]: https://github.com/janweinstock/vcml
[7]: https://github.com/aut0/avp64
[8]: https://git.minres.com/VP/HIFIVE1-VP
[9]: https://github.com/janweinstock/or1kmvp
[10]: https://github.com/Minres/TGC-VP
[11]: https://github.com/accellera-official/PySysC
[12]: https://github.com/VP-Vibes/VPV-Peripherals
[13]: https://hlslibs.org/
[14]: https://github.com/intel/systemc-compiler
[15]: https://github.com/verilator/verilator
[16]: https://github.com/Xilinx/systemctlm-cosim-demo
[17]: https://git.greensocs.com/platforms/greensocs-cortex-a53
[18]: https://git.greensocs.com/platforms/greensocs-neoverse-n1
[19]: https://git.greensocs.com/platforms/greensocs-riscv64
[20]: http://www.cecs.uci.edu/~doemer/risc.html
[21]: https://www.accellera.org/images/downloads/drafts-review/uvm-systemc-10-beta3tar.gz
[22]: https://forums.accellera.org/files/file/65-uvm-ml-open-architecture/
[23]: https://verificationacademy.com/topics/verification-methodology/uvm-connect
[24]: https://github.com/hsa-ees/paranut

[50]: https://www.accellera.org/images/downloads/standards/systemc/systemc-2.3.3.tar.gz
[51]: https://www.coseda-tech.com/systemc-ams-proof-of-concept