# Qavicorex
A custom multi-core RISC-V processor built on Chipyard with native AI acceleration and Linux boot support.
Overview

QaviCoreX is an experimental open-source processor project focused on combining modern RISC-V architecture with AI-oriented hardware extensions. The project explores custom processor design, Linux-capable system integration, and future FPGA implementation.

Current goals include:

Multi-core RISC-V architecture
Linux-capable platform
Custom AI instruction extensions
Chipyard-based SoC generation
FPGA deployment
Open-source development


Features
Custom Chipyard configuration
BOOM-based RISC-V cores
BootROM integration
OpenSBI support
Linux boot infrastructure
UART console
Configurable memory hierarchy
Modular Scala-based hardware configuration


Current Status
Component	Status
Chipyard Build	✅ Complete
SoC Generation	✅ Complete
BootROM	✅ Working
OpenSBI Integration	✅ Working
UART	✅ Working
Linux Boot	🚧 In Progress
FPGA Validation	⏳ Planned


Project Structure
configs/
docs/
bootrom/
scripts/
patches/
Build
source env.sh

cd sims/verilator

make CONFIG=QaviLinuxConfig -j4


Future Roadmap
Linux boot completion
AI accelerator instructions
Custom vector extensions
Cache optimization
FPGA deployment
Performance benchmarking
Motivation

QaviCoreX was started as a learning-driven project to explore modern processor architecture and AI hardware acceleration using the open RISC-V ecosystem. The long-term vision is to build a capable and extensible research platform for computer architecture and machine learning workloads.

Tech Stack
Scala
Chisel
Chipyard
BOOM
Rocket Chip
Verilator
OpenSBI
Linux
RISC-V
License

MIT License

Author

Syed Qavi Uddin



## Acknowledgment: QaviCoreX is built on top of the Chipyard ecosystem developed by UC Berkeley and the RISC-V open-source community. This repository contains the custom configurations, modifications, and documentation created for the QaviCoreX project. The upstream Chipyard framework is maintained separately under its own license.
