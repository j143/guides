---
lang: en
title: RISC-V Guide
description: RISC-V Guide
class: beginners
order: 2
image: https://user-images.githubusercontent.com/45159366/121087082-d35d5e00-c798-11eb-94bb-58bf863bd724.png
related:
  - finding
  - building
---

> A guide covering the RISC-V Architecture including the applications, libraries and tools that will make you a better and more efficient developer with the RISC-V ISA.


# Models of RISC-V boards

[Back to the Top](#table-of-contents)

[Checkout the StarFive VisionFive 8GB RISC-V SBC](https://www.aliexpress.com/item/3256803492307592.html)

 <img src="https://user-images.githubusercontent.com/45159366/171485293-3988aea2-a6da-49bb-9e8d-0af066d1f229.png">
 
 **StarFive VisionFive Hardware Specs**
 
**CPU:** U74 Dual-Core with 2MB L2 cache, running at 1.0GHz. The SoC includes Vision DSP Tensilica-VP6 for computing vision at 600MHz (VPU), an NVIDIA  Deep Learning Accelerator, and a neural network engine.

**Memory:** 8GB LPDDR4 RAM (2x 4GB clocked at 2800MHz)

**User I/O**
- 4 x USB3.0 Ports, Gigabit Ethernet, Audio jack
- 40 Pin GPIO Header (28 x GPIO, I2C, I2S, SPI, UART)

**Networking:** Wi-Fi and Bluetooth 4.2

Linux Ready including **Fedora**.

[Checkout the HiFive Unmatched Developement board](https://www.sifive.com/boards/hifive-unmatched) **(Discontinued as of January 2022)**

<img src="https://user-images.githubusercontent.com/45159366/104135527-ea149b80-5345-11eb-902a-f07b7bd0b99b.png">

**HiFive Unmatched Hardware Specs**

**SoC:** SiFive Freedom U740 SoC

**Memory:** 16GB DDR4

**Flash Memory:** 32MB Quad SPI Flash

**Removable Storage:** MicroSD Card

**Networking:** Gigabit Ethernet Port

**User I/O**

 - 4x USB 3.2 Gen 1 Type A Ports (1 Charging Port)

 - 1x MicroUSB Console Port

**Expansion Capabilities**

 - x16 PCIe® Gen 3 Expansion Slot (8-lanes Useable)

 - M.2 M-Key Slot (PCIe Gen 3 x4) for NVME 2280 SSD Module

 - M.2 E-Key Slot (PCIe Gen 3 x1) for Wi-Fi / Bluetooth Module

**Board Form Factor:** Industry Standard Mini-ITX


[Checkout the HiFive1 Rev B Developement board](https://www.sifive.com/boards/hifive1-rev-b)

<img src="https://user-images.githubusercontent.com/45159366/104135528-eb45c880-5345-11eb-8e47-22acd5a90e01.jpg">

**HiFive1 Rev B Hardware Specs**

**Microcontroller:** [FE310-G002](https://sifive.com/chip-designer#fe310)

**Operating Voltage:** 3.3 V and 1.8 V

**Input Voltage:** 5 V USB or 7-12 VDC Jack

**IO Voltage:** 3.3 V

**Digital I/O Pins:** 19

**PWM Pins:** 9

**SPI Controllers/HW CS Pins:** 1/3

**UART:** 2

**I2C:** 1

**Networking:** WiFi/BT (off-chip)

**External Interrupt Pins:** 19

**External Wakeup Pins:** 1

**Flash Memory:** 32 Mbit Off-Chip (ISSI SPI Flash)

**Host Interface (microUSB):** Program, Debug, and Serial Communication


[Checkout the Sipeed Maixduino Kit for RISC-V AI + IoT](https://www.seeedstudio.com/sipeed-maix.html)

[MAIX AI module](https://www.seeedstudio.com/Sipeed-MAIX-I-module-WiFi-version-1st-RISC-V-64-AI-Module-K210-inside-p-3206.html)

<img src="https://user-images.githubusercontent.com/45159366/104135531-ed0f8c00-5345-11eb-9c7d-d77f97bc16d5.jpeg">


**Sipeed Maixduino Kit Hardware Specs**

 - **CPU:** RISC-V Dual Core 64bit, with FPU; 400MHz neural network processor

 - QVGA@60FPS/VGA@30FPS image identification

 - Onboard ESP32 module support 2.4G 802.11. b/g/n and Bluetooth 4.2

 - [Arduino Uno](https://store.arduino.cc/usa/arduino-uno-rev3) form factor, Arduino compatible interface

 - Onboard omnidirectional I2S digital output MEMS Microphone

 - 24P 0.5mm FPC connector for DVP Camera

 - 8-bit MCU LCD 24P 0.5mm FPC connector

 - Support self-elastic micro SD card holder
 
 - High performance microphone array processor for machine hearing
 
 - Support MaixPy IDE, Arduino IDE, OpenMV IDE, and PlatformIO IDE
 
 - Support Tiny-Yolo, Mobilenet and TensorFlow Lite for deep learning
 
 
[Checkout the RTG4 Development Kit board from Microsemi](https://www.microsemi.com/product-directory/dev-kits-solutions/3865-rtg4-kits)

 <img src="https://user-images.githubusercontent.com/45159366/104135532-ee40b900-5345-11eb-9830-f57fe6d94f6f.jpeg">


**RTG4 Development Kit Hardware Specs**

 - Two 1GB DDR3 synchronous dynamic random access memory (SDRAM)
 
 - 2GB SPI flash memory
 
 - PCI Express Gen 1 x1 interface
 
 - PCIe x4 edge connector
 
 - One pair SMA connectors for testing of the full-duplex SERDES channel

 - Two FMC connectors with HPC/LPC pinout for expansion

 - RJ45 interface for 10/100/1000 Ethernet
 
 - USB micro-AB connector

 - Headers for SPI, GPIOs

 - FTDI programmer interface to program the external SPI flash

 - JTAG programming interface
 
**[Checkout the Espressif ESP32-C3](https://www.espressif.com/en/products/socs/esp32-c3)**

[Espressif ESP32-C3](https://www.espressif.com/en/products/socs/esp32-c3) is a single-core Wi-Fi and Bluetooth 5 (LE) microcontroller SoC, based on the open-source RISC-V architecture. It has the right balance of power, I/O capabilities and security, thus offering the optimal cost-effective solution for connected devices. The availability of Wi-Fi and Bluetooth 5 (LE) connectivity not only makes the device's configuration easy, but it also facilitates a variety of use-cases based on dual connectivity.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/177451635-64cda8af-b05f-4506-acc1-d9ddf5a894f1.png">
  <br />
</p>

**Espressif ESP32-C3 Hardware Specs:**

- 32-bit core RISC-V microcontroller with a maximum clock speed of 160 MHz. 
- 22 configurable GPIOs.
- 400 KB of internal RAM. 
- Low-power-mode support.
- RSA-3072-based secure boot.
- AES-128/256-XTS-based flash encryption.
- Wi-Fi and Bluetooth 5 (LE).

[Espressif ESP32-C3-DevKitC-02](https://docs.espressif.com/projects/esp-idf/en/latest/esp32c3/hw-reference/esp32c3/user-guide-devkitc-02.html) is an entry-level development board based on [ESP32-C3-WROOM-02](https://www.espressif.com/sites/default/files/documentation/esp32-c3-wroom-02_datasheet_en.pdf), a general-purpose module with 4 MB SPI flash. This board integrates complete Wi-Fi and Bluetooth LE functions.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/177451653-b77a9819-2308-4080-b2dd-8aec755b5583.png">
  <br />
  ESP32-C3-DevKitC-02
</p>

[Espressif ESP32-C3-DevKitM-1](https://docs.espressif.com/projects/esp-idf/en/latest/esp32c3/hw-reference/esp32c3/user-guide-devkitm-1.html) is an entry-level development board based on [ESP32-C3-MINI-1](https://www.espressif.com/sites/default/files/documentation/esp32-c3-mini-1_datasheet_en.pdf), a module named for its small size. This board integrates complete Wi-Fi and Bluetooth LE functions.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/177451647-4831fad4-8fc9-4c50-858f-dbb11c829df8.png">
  <br />
  ESP32-C3-DevKitM-1
</p>

# RISC-V Learning Resources

[Back to the Top](#table-of-contents)


[RISC-V Foundation](https://riscv.org/) is a non-profit corporation controlled by its 500 members(NVIDIA, Google, Samsung, Raspberry Pi, SiFive, Canonical, and Western Digital) to drive forward the adoption and implementation of the free and open RISC-V instruction set architecture (ISA).

[SiFive](https://www.sifive.com/) is a semiconductor company that produces complete RISC-V processors IP with pre-integrated SiFive Shield, for whole SoC security, and SiFive Insight advanced trace and debug. 

[IAR Systems](https://www.iar.com/) is a company that enables Linux-based Continuous Integration and automated workflows for embedded systems(ARM & RISC-V).

### Developer Resources
[Back to the Top](https://github.com/mikeroyal/risc-v-Guide#table-of-contents)

- [RISC-V Cores and SoC Overview](https://riscv.org/risc-v-cores/)

- [Optimizing OpenCV for the RISC-V Architecture](https://opencv.org/optimizing-opencv-for-the-risc-v-architecture/)

- [Software development kits, Toolchains and Utilities for RISC-V devices](https://www.sifive.com/software)

- [RISC-V Development Board and RISC-V CPU](https://risc-v.ca)

- [RISC-V CPUs from Microsemi](https://www.microsemi.com/product-directory/mi-v-risc-v-ecosystem/4406-risc-v-cpus#overview)

- [RISC-V Community](https://riscv.org/community/)

- [RISC-V Main Members Group](https://lists.riscv.org/g/main)

- [RISC-V Global Forum](https://events.linuxfoundation.org/riscv-global-forum/)

### Learning/Training Courses
[Back to the Top](https://github.com/mikeroyal/risc-v-Guide#table-of-contents)

- [RISC-V Learn Online Courses](https://riscv.org/community/learn/risc-v-learn-online/)

- [RISC-V Training Partner Program](https://riscv.org/exchange/training-partner-program/)

- [SiFive Academy RISC-V Course](https://www.sifiveacademy.com/)

- [Risc-V Courses on Udemy](https://www.udemy.com/topic/risc-v/)

- [Imagination Technologies Announces the First RISC-V Computer Architecture Course](https://riscv.org/news/2020/09/imagination-announces-the-first-risc-v-computer-architecture-course/)

 - [RISC-V Design Verification Strategy](https://verificationacademy.com/verification-horizons/november-2020-volume-16-issue-3/risc-v-design-verification-strategy)
 
 ### Books
 [Back to the Top](https://github.com/mikeroyal/risc-v-Guide#table-of-contents)
 
 - [The RISC-V Instruction Set Manual](https://riscv.org/wp-content/uploads/2019/12/riscv-spec-20191213.pdf)
 
 - [RISC-V Assembly Programmer's Manual](https://github.com/riscv-non-isa/riscv-asm-manual/blob/master/riscv-asm.md)
 
 - [Digital Design and Computer Architecture, RISC-V Edition](https://www.amazon.com/Digital-Design-Computer-Architecture-RISC-V/dp/0128200642)
 
 - [Computer Organization and Design RISC-V Edition (The Morgan Kaufmann Series in Computer Architecture and Design)](https://www.amazon.com/Computer-Organization-Design-RISC-V-Architecture/dp/0128203315)
 
 - [The RISC-V Reader: An Open Architecture Atlas ](https://www.amazon.ca/RISC-V-Reader-Open-Architecture-Atlas/dp/0999249118)
 
 - [An Introduction to Assembly Programming with RISC-V](https://riscv-programming.org/book.html)

 - [Digital Design with Chisel Book](https://github.com/schoeberl/chisel-book)

# RISC-V Operating Systems

[Back to the Top](#table-of-contents)

[Running 32-bit & 64-bit RISC-V Linux on QEMU](https://risc-v-getting-started-guide.readthedocs.io/en/latest/linux-qemu.html)

 - [FreeRTOS](https://freertos.org/) 

 - [Zephyr OS](https://www.zephyrproject.org/zephyr-rtos-featured-in-risc-v-getting-started-guide/) 

 - [meta-riscv AKA OpenEmbedded/Yocto](https://github.com/riscv/meta-riscv)

 - [RISC-V - Ubuntu Wiki](https://wiki.ubuntu.com/RISC-V)

 - [RISC-V - Kubuntu Wiki](https://wiki.kubuntu.org/RISC-V)

 - [RISC-V - Debian Wiki](https://wiki.debian.org/RISC-V)

 - [RISC-V - Fedora Project Wiki](https://fedoraproject.org/wiki/Architectures/RISC-V)

 - [RISC-V - openSUSE Wiki](https://en.opensuse.org/openSUSE:RISC-V)

 - [RISC-V - FreeBSD Wiki](https://wiki.freebsd.org/riscv)

 - [RISC-V - OpenBSD Wiki](https://www.openbsd.org/riscv64.html)

 - [Huawei LiteOS](https://www.huawei.com/minisite/liteos/en/index.html)

 - [Apache Mynewt](https://mynewt.apache.org/)

 - [Apache NuttX](https://nuttx.apache.org/)

 - [Drone OS](https://www.drone-os.com/)

 - [embOS](https://www.segger.com/products/rtos/embos/)

 - [Little Kernel Embedded Operating System](https://github.com/littlekernel/lk/)

 - [Tock OS](https://www.tockos.org/)

 - [TrampolineRTOS](https://github.com/TrampolineRTOS/trampoline)

 - [RIOT](https://www.riot-os.org/)  
 

## RISC-V Tools

[Back to the Top](#table-of-contents)

[Rocket Chip Generator](https://github.com/chipsalliance/rocket-chip) is a repository contains the Rocket chip generator necessary to instantiate the RISC-V Rocket Core.

[CORE-V CVA6](https://github.com/openhwgroup/cva6) is an application class 6-stage RISC-V CPU capable of booting Linux.

[Cores-SweRV](https://github.com/chipsalliance/Cores-SweRV) is the EH1 RISC-V SweRV CoreTM 1.9 from Western Digital. 

[VRoom](https://github.com/MoonbaseOtago/vroom) is a new high-end RISC-V CPU implementation.

[FireSim](https://fires.im/) is an open-source cycle-accurate FPGA-accelerated full-system hardware simulation platform that runs on cloud FPGAs (Amazon EC2 F1).

[Nuclei Software Development Kit(Nuclei SDK)](https://doc.nucleisys.com/nuclei_sdk) is a toolkit for developing and evaluating software using our FPGA evaluation board.

[GAP SDK](https://github.com/GreenWaves-Technologies/gap_sdk) is set of tools and libraries that allows you to compile and execute applications on the GAP IoT Application Processor. This SDK provides a development environment for the GAP series processors.

[RISC-V Studio™ Integrated Development Environment (IDE)](https://riscv.studio) is a flexible and highly configurable software environment that helps the RISC-V developers discover, configure, develop, debug and deploy system designs utilizing open-source and commercial RISC-V IPs and platforms.

[Ashling RiscFree™ C/C++ for RISC-V](https://www.sifive.com/software) is a fully integrated development tool environment that includes an IDE, compiler, debugger, and Opella-XD JTAG probe ready to use with SiFive's RISC-V Core IP products. 

[RISCVEMU](https://riscv.org/software-tools/riscvemu/) is a system emulator developed by Fabrice Bellard for the RISC-V architecture. Its purpose is to be small and simple while being complete. Among its features are the support of 128 bit addressing and 128 bit floating point which makes the emulator ready for the future.

[RISC-V Interpreter](http://www.cs.cornell.edu/courses/cs3410/2019sp/riscv/interpreter/) is a online Interpreter for RISC-V build by Cornell University.

[Chipyard](https://chipyard.readthedocs.io/en/latest/) is an open source framework for agile development of Chisel-based systems-on-chip. It will allow you to leverage the Chisel HDL, Rocket Chip SoC generator, and other [Berkeley](https://berkeley.edu/) projects to produce a RISC-V SoC with everything from MMIO-mapped peripherals to custom accelerators.

[BRISC-V Explorer](https://ascslab.org/research/briscv/explorer/explorer.html) is a RISC-V CPU simulator application that runs in a browser allowing users to easily run it on Windows, Linux or Mac. In the BRISC-V Explorer, users can 

  - 1. Select their desired core type.
  - 2. Enter parameters such as memory size for that core.
  - 3. Configure cache parameters including block size and associativity.
  
 
[Ripes](https://github.com/mortbopet/Ripes) is a graphical processor simulator and assembly editor for the RISC-V instruction set architecture(ISA).

[OpenHW Group's RISC-V Virtual Machine (riscv_vm)](https://github.com/openhwgroup/riscv_vm/) is a set of instructions to import Ubuntu guest Virtual Machine for RISC-V development for the VEGA board. It's intended for anyone wanting to study, configure as-preferred, modify, implement or release hardware based the RISC-V Instruction Set Architecture. The VM is preconfigured for RISC-V HW development. 

[The Eclipse Embedded CDT](https://github.com/eclipse-embed-cdt/eclipse-plugins) is a collection of plug-ins for Arm & RISC-V C/C++ developers.

[PlatformIO](https://platformio.org/) is a professional collaborative platform for embedded development with no vendor lock-in. It provides support for multiplatforms and frameworks such as IoT, Arduino, CMSIS, ESP-IDF, FreeRTOS, libOpenCM3, mbed OS, Pulp OS, SPL, STM32Cube, Zephyr RTOS, ARM, AVR, Espressif (ESP8266/ESP32), FPGA, MCS-51 (8051), MSP430, Nordic (nRF51/nRF52), NXP i.MX RT, PIC32, RISC-V.

[PlatformIO for VSCode](https://marketplace.visualstudio.com/items?itemName=platformio.platformio-ide) is a plugin that provides support for the PlatformIO IDE on VSCode.

[Tock](https://www.tockos.org/) is an embedded operating system designed for running multiple concurrent, mutually distrustful applications on Cortex-M and RISC-V based embedded platforms. Tock's design centers around protection, both from potentially malicious applications and from device drivers. 

[TinyGo](https://tinygo.org/) is a Go compiler(based on LLVM) intended for use in small places such as microcontrollers, WebAssembly (Wasm), and command-line tools.

[LLVM](https://github.com/llvm/) is a library that has collection of modular/reusable compiler and toolchain  components (assemblers, compilers, debuggers, etc.). With these components LLVM can be used as a compiler framework, providing a front-end(parser and lexer) and a back-end (code that converts LLVM's representation to actual machine code).

[Unicorn](https://github.com/unicorn-engine/unicorn) is a lightweight, multi-platform, multi-architecture CPU emulator framework(ARM, AArch64, M68K, Mips, Sparc, X86) based on [QEMU](https://www.qemu.org/).

[Keystone](https://github.com/keystone-engine/keystone) is a lightweight multi-platform, multi-architecture(Arm, Arm64, Hexagon, Mips, PowerPC, Sparc, SystemZ & X86) assembler framework.

[Reko](https://github.com/uxmal/reko) is a decompiler for machine code binaries.

[Renode](https://renode.io/) is [Antmicro's](https://antmicro.com) virtual development framework for multinode embedded networks (both wired and wireless) and is intended to enable a scalable workflow for creating effective, tested and secure IoT systems.

[Jupiter](https://jupitersim.gitbook.io/) is an open source and education-oriented RISC-V assembler and runtime simulator written in Java.

[RISC-V Rust](https://github.com/takahirox/riscv-rust) is a RISC-V processor and peripheral devices emulator project written in Rust and compiled to WebAssembly.

[Diosix](https://diosix.org/) is a lightweight, secure, multiprocessor bare-metal hypervisor written in Rust for RISC-V.

[Maixpy](https://maixpy.sipeed.com/) is designed to make AIOT programming easier with Micropython running on the embedded AIOT chip [K210](https://kendryte.com/).

[DarkRISCV](https://github.com/darklife/darkriscv) is an open souce RISC-V cpu core implemented in Verilog from scratch.

# FPGA Development

[Back to the Top](#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/104069966-ab060f00-51ba-11eb-8295-d3479b485c86.png">
  <br />
</p>

## Models of FPGA Boards

[Checkout the PolarFire® FPGA Development Kits](https://www.microsemi.com/product-directory/dev-kits-solutions/3864-polarfire-kits)

<img src="https://user-images.githubusercontent.com/45159366/104068349-97a67400-51b9-11eb-82b5-d06f804400ee.png">


[Checkout the Artix 7 FPGA Development board](https://store.digilentinc.com/basys-3-artix-7-fpga-trainer-board-recommended-for-introductory-users/)

<img src="https://user-images.githubusercontent.com/45159366/104068359-9d03be80-51b9-11eb-9bd2-0045e8f45eb9.png">


[Checkout the Spartan 6 FPGA Development board](https://store.digilentinc.com/anvyl-spartan-6-fpga-trainer-board/)

<img src="https://user-images.githubusercontent.com/45159366/104068361-9e34eb80-51b9-11eb-9c68-0b59c5a107e1.png">



[Checkout the Zynq-7000 for ARM/FPGA SoC Development board](https://store.digilentinc.com/cora-z7-zynq-7000-single-core-and-dual-core-options-for-arm-fpga-soc-development/)

<img src="https://user-images.githubusercontent.com/45159366/104068367-a12fdc00-51b9-11eb-966a-08a0868fcfb7.png">


## FPGA Learning Resources
 
[FPGA(Field Programmable Gate Arrays)](https://www.xilinx.com/products/silicon-devices/fpga/what-is-an-fpga.html) are semiconductor devices that are based around a matrix of configurable logic blocks (CLBs) connected via programmable interconnects. FPGAs can be reprogrammed to desired application or functionality requirements after manufacturing.

[TinyFPGA](https://tinyfpga.com) is a new series of boards that are low-cost, [open source FPGA boards](https://github.com/tinyfpga) in a tiny form factor.

[SiFive FPGA shells](https://github.com/sifive/fpga-shells)

[FPGA & SoC Design Tools from Microsemi](https://www.microsemi.com/product-directory/fpga-soc/1637-design-resources)

[QuickLogic Embedded FPGA (eFPGA) Intellectual Property (IP) and Software](https://www.quicklogic.com/products/efpga/efpga-ip-software/)

[FPGA for Beginners with Development Boards from Digilent®](https://store.digilentinc.com/fpga-for-beginners/)

[Hundreds of FPGA Projects on Instructables](https://www.instructables.com/circuits/howto/FPGA/)
 
[FPGA Fundamentals from NI(National Instruments)](https://www.ni.com/en-us/innovations/white-papers/08/fpga-fundamentals.html)

[Getting Started With LabVIEW FPGA from NI(National Instruments)](https://www.ni.com/tutorial/14532/en/)
 
[Programming and FPGA Basics - INTEL® FPGAS](https://www.intel.com/content/www/us/en/products/programmable/fpga/new-to-fpgas/resource-center/overview.html)
 
[Intel FPGA Training Program](https://www.intel.com/content/www/us/en/programmable/support/training/overview.html)
 
[FPGA Courses on Coursera](https://www.coursera.org/courses?query=fpga)
 
[FPGA Courses on Udemy](https://www.udemy.com/topic/fpga/)
 
[FPGA Online Training Courses on LinkedIn Learning](https://www.linkedin.com/learning/topics/fpga)

[UMass Lowell's Graduate Certificate in Field Programmable Gate Arrays(FPGA)](https://gps.uml.edu/certificates/grad/online-field-programmable-gate-arrays-bae-graduate-certificate.cfm)

[FPGA Design Fundamentals Course (UC San Diego Extension)](https://extension.ucsd.edu/courses-and-programs/fpga-design-fundamentals)

[FPGA II Course (UC San Diego Extension)](https://extension.ucsd.edu/courses-and-programs/fpga-embedded-design)

[FPGAs & SoCs Training from Microsemi](https://www.microsemi.com/product-directory/training/4244-fpgas-socs-training)
 
[DSP fundamentals for FPGAs course from MATLAB and Simulink Training](https://www.mathworks.com/training-schedule/dsp-for-fpgas.html)
 
[Verilog Courses on Coursera](https://www.coursera.org/courses?query=verilog)


## FPGA Tools

[LabVIEW FPGA](https://www.ni.com/en-us/shop/software/products/labview-fpga-module.html) is a software add-on for LabVIEW that you can use to more efficiently and effectively design FPGA-based systems through a highly integrated development environment, IP libraries, a high-fidelity simulator, and debugging features.

[Apio](https://github.com/FPGAwars/apio) is a multiplatform toolbox, with static pre-built packages, project configuration tools and easy command interface to verify, synthesize, simulate and upload your verilog designs.

[IceStorm](https://github.com/YosysHQ/icestorm) is a project that aims at documenting the bitstream format of Lattice iCE40 FPGAs and providing simple tools for analyzing and creating bitstream files.

[Icestudio](https://icestudio.io/) is a visual editor for open FPGA boards. Built on top of the Icestorm project using Apio.

[FuseSoC](https://github.com/olofk/fusesoc) is an award-winning package manager and a set of build tools for HDL (Hardware Description Language) code and FPGA/ASIC development.
 
[OpenWiFi](https://github.com/open-sdr/openwifi) is an open-source IEEE802.11/Wi-Fi baseband chip/FPGA design.
 
[PipeCNN](https://github.com/doonny/PipeCNN) is an OpenCL-based FPGA Accelerator for Large-Scale Convolutional Neural Networks (CNNs). Currently, there is a growing trend among developers in the FPGA community to utilize High Level Synthesis (HLS) tools to design and implement customized circuits on FPGAs.

[Verilator](https://verilator.org/) is an open-source SystemVerilog simulator and lint system.

[Verilog to Routing(VTR)](https://verilogtorouting.org/) is a collaborative project to provide a open-source framework for conducting FPGA architecture and CAD Research & Development. The VTR design flow takes as input a Verilog description of a digital circuit, and a description of the target FPGA architecture.

[PlatformIO](https://platformio.org/) is a professional collaborative platform for embedded development with no vendor lock-in. It provides support for multiplatforms and frameworks such as IoT, Arduino, CMSIS, ESP-IDF, FreeRTOS, libOpenCM3, mbed OS, Pulp OS, SPL, STM32Cube, Zephyr RTOS, ARM, AVR, Espressif (ESP8266/ESP32), FPGA, MCS-51 (8051), MSP430, Nordic (nRF51/nRF52), NXP i.MX RT, PIC32, RISC-V.

[PlatformIO for VSCode](https://marketplace.visualstudio.com/items?itemName=platformio.platformio-ide) is a plugin that provides support for the PlatformIO IDE on VSCode.
 
[Tock](https://www.tockos.org/) is an embedded operating system designed for running multiple concurrent, mutually distrustful applications on Cortex-M and RISC-V based embedded platforms. Tock's design centers around protection, both from potentially malicious applications and from device drivers. 

[OpenTimer](https://github.com/OpenTimer/OpenTimer) is a High-Performance Timing Analysis Tool for VLSI Systems.

[LLVM](https://github.com/llvm/) is a library that has collection of modular/reusable compiler and toolchain  components (assemblers, compilers, debuggers, etc.). With these components LLVM can be used as a compiler framework, providing a front-end(parser and lexer) and a back-end (code that converts LLVM's representation to actual machine code).

[TinyGo](https://tinygo.org/) is a Go compiler(based on LLVM) intended for use in small places such as microcontrollers, WebAssembly (Wasm), and command-line tools.

[Chipyard](https://chipyard.readthedocs.io/en/latest/) is an open source framework for agile development of Chisel-based systems-on-chip. It will allow you to leverage the Chisel HDL, Rocket Chip SoC generator, and other [Berkeley](https://berkeley.edu/) projects to produce a RISC-V SoC with everything from MMIO-mapped peripherals to custom accelerators.

[The Eclipse Embedded CDT](https://github.com/eclipse-embed-cdt/eclipse-plugins) is a collection of plug-ins for Arm & RISC-V C/C++ developers.
[Unicorn](https://github.com/unicorn-engine/unicorn) is a lightweight, multi-platform, multi-architecture CPU emulator framework(ARM, AArch64, M68K, Mips, Sparc, X86) based on [QEMU](https://www.qemu.org/).

[Keystone](https://github.com/keystone-engine/keystone) is a lightweight multi-platform, multi-architecture(Arm, Arm64, Hexagon, Mips, PowerPC, Sparc, SystemZ & X86) assembler framework.

[Reko](https://github.com/uxmal/reko) is a decompiler for machine code binaries.

[Renode](https://renode.io/) is [Antmicro's](https://antmicro.com) virtual development framework for multinode embedded networks (both wired and wireless) and is intended to enable a scalable workflow for creating effective, tested and secure IoT systems.

[Diosix](https://diosix.org/) is a lightweight, secure, multiprocessor bare-metal hypervisor written in Rust for RISC-V.

# Verilog/SystemVerilog Development

[Back to the Top](#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/102273517-4b785480-3ed7-11eb-910a-113821428f17.png">
  <br />

</p>

## Verilog/SystemVerilog Learning Resources

[Verilog](https://verilog.com/) is a Hardware Description Language(HDL) used to design and document electronic systems. Verilog HDL allows designers to design at various levels of abstraction.

[SystemVerilog](https://www.systemverilog.io/) is an extension of Verilog with many of the verification features that allow engineers to verifythe design using complex testbench structures and random stimuli in simulation. 

[Verilog Book Shelf](https://verilog.com/v-books.html)

[Verilog HDL Basics training from Intel](https://www.intel.com/content/www/us/en/programmable/support/training/course/ohdl1120.html)

[SystemVerilog for Design and Verification](https://www.cadence.com/en_US/home/training/all-courses/82143.html)

[Verilog HDL Programming Courses on Udemy](https://www.udemy.com/topic/verilog-hdl-programming/)

[Top Verilog Programming Courses on Coursera](https://www.coursera.org/courses?query=verilog)

[Verilog course for Engineers on Technobyte](https://technobyte.org/verilog-course-tutorials/)

[Verilog Tutorials and Courses on hackr.io](https://hackr.io/tutorials/learn-verilog)

[Designing With Verilog Certification from the Xilinx Learning Center](https://xilinxprod-catalog.netexam.com/Certification/35916/designing-with-verilog)

[Learning Verilog for FPGA Development on LinkedIn Learning](https://www.linkedin.com/learning/learning-verilog-for-fpga-development)

[SystemVerilog tutorial on ChipVerify](https://www.chipverify.com/systemverilog/systemverilog-tutorial)

## Verilog/SystemVerilog Tools

[Apio](https://github.com/FPGAwars/apio) is a multiplatform toolbox, with static pre-built packages, project configuration tools and easy command interface to verify, synthesize, simulate and upload your verilog designs.

[IceStorm](https://github.com/YosysHQ/icestorm) is a project that aims at documenting the bitstream format of Lattice iCE40 FPGAs and providing simple tools for analyzing and creating bitstream files.

[Icestudio](https://icestudio.io/) is a visual editor for open FPGA boards. Built on top of the Icestorm project using Apio.

[EDA Playground](https://www.edaplayground.com) is a online code for programming your Verilog projects.

[PlatformIO](https://platformio.org/) is a professional collaborative platform for embedded development with no vendor lock-in. It provides support for multiplatforms and frameworks such as IoT, Arduino, CMSIS, ESP-IDF, FreeRTOS, libOpenCM3, mbed OS, Pulp OS, SPL, STM32Cube, Zephyr RTOS, ARM, AVR, Espressif (ESP8266/ESP32), FPGA, MCS-51 (8051), MSP430, Nordic (nRF51/nRF52), NXP i.MX RT, PIC32, RISC-V.

[PlatformIO for VSCode](https://marketplace.visualstudio.com/items?itemName=platformio.platformio-ide) is a plugin that provides support for the PlatformIO IDE on VSCode.

[Chisel](https://www.chisel-lang.org/) is a hardware design language that facilitates advanced circuit generation and design reuse for both ASIC and FPGA digital logic designs. Chisel adds hardware construction primitives to the [Scala](https://www.scala-lang.org/) programming language, providing designers with the power of a modern programming language to write complex, parameterizable circuit generators that produce synthesizable Verilog.

[Clash compiler](https://www.clash-lang.org/) is a functional hardware description language that borrows both its syntax and semantics from the functional programming language Haskell. The Clash compiler transforms these high-level descriptions to low-level synthesizable VHDL, Verilog, or SystemVerilog.

[Verilator](https://verilator.org/) is an open-source SystemVerilog simulator and lint system.

[Verilog to Routing(VTR)](https://verilogtorouting.org/) is a collaborative project to provide a open-source framework for conducting FPGA architecture and CAD Research & Development. The VTR design flow takes as input a Verilog description of a digital circuit, and a description of the target FPGA architecture.

[Cascade](https://github.com/vmware/cascade) is a Just-In-Time Compiler for Verilog from VMware Research. Cascade executes code immediately in a software simulator, and performs compilation in the background. When compilation is finished, the code is moved into hardware, and from the user’s perspective it simply gets faster over time.

[OpenTimer](https://github.com/OpenTimer/OpenTimer) is a High-Performance Timing Analysis Tool for VLSI Systems.

# Assembly Development
[Back to the Top](#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/101415607-18154480-389d-11eb-80e8-17a5c57e480f.png">
  <br />
</p>

**[Learn Risc-V Assembly Programming](https://riscv.org/news/2021/01/learn-risc-v-assembly-programming-lesson1-for-absolute-beginners-chibiakumas/)**

## Assembly Learning Resources

[Assembly](https://en.wikipedia.org/wiki/Assembly_language) is a low-level programming language. It uses mnemonic codes and labels to represent machine-level code with each instruction corresponding to just one machine operation.

[RISC-V Foundation](https://riscv.org/) is a non-profit corporation controlled by its 500 members(NVIDIA, Google, Samsung, Raspberry Pi, SiFive, Canonical, and Western Digital) to drive forward the adoption and implementation of the free and open RISC-V instruction set architecture (ISA).

[Intel® 64 and IA-32 Architectures Software Developer’s Manual](https://software.intel.com/content/www/us/en/develop/articles/intel-sdm.html)

[Introduction to x64 Assembly from Intel](https://software.intel.com/content/www/us/en/develop/articles/introduction-to-x64-assembly.html)

[x86 Assembly Language Reference Manual for Open Solaris](https://docs.oracle.com/cd/E19120-01/open.solaris/817-5477/index.html)

[AMD64 Architecture Programmer’s Manual Volume 1-5](https://www.amd.com/system/files/TechDocs/40332.pdf)

[AMD GPU ISA documentation](https://gpuopen.com/documentation/amd-isa-documentation/)

[AMD Developer Guides, Manuals, and ISA Documents](https://developer.amd.com/resources/developer-guides-manuals/)

[Assembler language from IBM](https://www.ibm.com/support/knowledgecenter/en/SSLTBW_2.1.0/com.ibm.zos.v2r1.asma400/asmr102112.htm)

[The Assembler language on z/OS from IBM](https://www.ibm.com/support/knowledgecenter/zosbasics/com.ibm.zos.zappldev/zappldev_25.htm)

[MIPS Architecture & Technology from Wave Computing](https://wavecomp.ai/mips-technology/)

[Assemblies in .NET](https://docs.microsoft.com/en-us/dotnet/standard/assembly/)

[Microsoft Macro Assembler reference](https://docs.microsoft.com/en-us/cpp/assembler/masm/microsoft-macro-assembler-reference)

[Compiler Intrinsics and Assembly Language from Microsoft](https://docs.microsoft.com/en-us/cpp/intrinsics/compiler-intrinsics-and-assembly-language)

[x86 and amd64 instruction Reference](https://www.felixcloutier.com/x86/)

[Intro to x86 Assembly Language Programming](https://cs.lmu.edu/~ray/notes/x86assembly/)

[Learn Assembly Programming courses on Udemy](https://www.udemy.com/topic/assembly-language/)

[Assembly Languages and Assemblers courses on Coursera](https://www.coursera.org/lecture/build-a-computer/unit-6-1-assembly-languages-and-assemblers-l4EGm)

[Intro to Assembly Language from MIT](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/index.htm)


## Assembly Tools & Architectures

[Arm Instruction Emulator (ArmIE)](https://developer.arm.com/tools-and-software/server-and-hpc/compile/arm-instruction-emulator/resources/tutorials) is a tool that emulates Scalable Vector Extension (SVE) and SVE2 instructions on AArch64/ARM64 platforms. 

[FASM (flat assembler)](https://flatassembler.net/) is an assembler for x86 processors that supports Intel-based assembly language on the IA-32 and x86-64 computer architectures. 

[Microsoft Assembler (MASM) for x64](https://docs.microsoft.com/en-us/cpp/assembler/masm/masm-for-x64-ml64-exe) is Microsoft's assembler that accepts x64 assembler language. 

[MASM/TASM](https://github.com/xsro/masm-tasm) is a VSCode extension that offers a way to run and debug DOS(80x86) assembly TASM/MASM through DOSBox and msdos-player.

[NASM](https://nasm.us/) is an asssembler/disassembler for the x86 CPU architecture portable to nearly every modern platform, and with code generation for many platforms old and new.

[GAS](https://www.gnu.org/software/binutils/) is the assembler used by the GNU Project for the default back-end of GCC. It is used to assemble the GNU operating system and the Linux kernel.

[MIPS](https://en.wikipedia.org/wiki/MIPS_Technologies) is a reduced instruction set computer (RISC) instruction set architecture (ISA) developed by [MIPS Technologies, Inc.](https://www.mips.com/). In June 2018 [MIPS was Acquired by AI Startup Wave Computing](https://www.top500.org/news/mips-acquired-by-ai-startup-wave-computing/).

[LLVM](https://github.com/llvm/) is a library that has collection of modular/reusable compiler and toolchain  components (assemblers, compilers, debuggers, etc.). With these components LLVM can be used as a compiler framework, providing a front-end(parser and lexer) and a back-end (code that converts LLVM's representation to actual machine code).

[TinyGo](https://tinygo.org/) is a Go compiler(based on LLVM) intended for use in small places such as microcontrollers, WebAssembly (Wasm), and command-line tools.

[Tock](https://www.tockos.org/) is an embedded operating system designed for running multiple concurrent, mutually distrustful applications on Cortex-M and RISC-V based embedded platforms. Tock's design centers around protection, both from potentially malicious applications and from device drivers. 

[PlatformIO](https://platformio.org/) is a professional collaborative platform for embedded development with no vendor lock-in. It provides support for multiplatforms and frameworks such as IoT, Arduino, CMSIS, ESP-IDF, FreeRTOS, libOpenCM3, mbed OS, Pulp OS, SPL, STM32Cube, Zephyr RTOS, ARM, AVR, Espressif (ESP8266/ESP32), FPGA, MCS-51 (8051), MSP430, Nordic (nRF51/nRF52), NXP i.MX RT, PIC32, RISC-V.

[PlatformIO for VSCode](https://marketplace.visualstudio.com/items?itemName=platformio.platformio-ide) is a plugin that provides support for the PlatformIO IDE on VSCode.

[Keystone](https://github.com/keystone-engine/keystone) is a lightweight multi-platform, multi-architecture(Arm, Arm64, Hexagon, Mips, PowerPC, Sparc, SystemZ & X86) assembler framework.

[Unicorn](https://github.com/unicorn-engine/unicorn) is a lightweight, multi-platform, multi-architecture CPU emulator framework(ARM, AArch64, M68K, Mips, Sparc, X86) based on [QEMU](https://www.qemu.org/).

