### NErO

### 👋 Hi, I'm Nikita (aka NErO)

### Low-Level Systems Developer • Reverse Engineering & Kernel Security Research (Ring 0)

I am a systems programmer focused on OS internals, binary analysis, and low-level software engineering. I specialize in understanding software-to-hardware interaction, working with CPU instructions, system calling conventions, and machine-level memory layouts. 

### 🚀 Synopsis

* 💻 Programming since the age of **9**.
* ⚙️ Core Stack: **Modern C++ & x86-64 / ARM64 Assembly**.
* 🧩 Focus: **Systems Programming, Semantic Reverse Engineering, Kernel Architecture**.
* 🖥️ Platforms: In-depth study of Windows Internals & Linux Kernel structures.
* 🇬🇧 English: **B1 / Professional Working Proficiency (approaching B2)**.

### 🛠️ Tech Stack

**Languages & Architectures:** Modern C++ (STL, Concurrency), x86-64 Assembly (Proficient, Naked functions), Python (Automation & Scripting).
* **Architectures:** Intel VT-x/VMX, AMD-V, ARM64 Exception Levels (EL0-EL3), x86-64 Segmentation and Paging.
* **Reverse Engineering & Debugging:** IDA Pro, Ghidra, WinDbg (Kernel Debugging / KDNET), GDB, LLDB.
* **Systems & Technologies:** Windows Internals (IRP, Windows Kernel Pools, Driver Object Structures), Linux Kernel Architecture (POSIX, Modules, SLUB allocator), Boost.Asio (Asynchronous networking), OpenSSL, CMake, Ninja.

### 📂 Featured Systems Projects

### 💬 Asynchronous C++ Encrypted Messenger

A high-performance, asynchronous terminal-based communication engine built on modern C++ primitives. 

* **Architecture:** Driven by a non-blocking event loop using **Boost.Asio**.
* **Memory Management:** Implements asynchronous execution pipelines with explicit object lifetime controls (std::enable_shared_from_this, std::weak_ptr) to ensure safety in concurrent state machines.
* **Crypto & Storage:** Network layer encryption via **OpenSSL**, standalone chat history storage with an optimized **SQLite** engine.

### 🔬 Low-Level Assembly & Architecture Research

A collection of bare-metal and system-level code components written in pure **x86-64 and ARM64 Assembly**. 

* Research on Calling Conventions (Microsoft x64 ABI vs System V AMD64 ABI), context switching logic, and software-to-hardware transition states.
* Implementation of Naked functions, custom shellcodes, and optimized cryptographic/string algorithms.
* Code analysis laboratories focused on parsing Native API structures and semantic binary audit.

### 🖥️ Linux Remote Administration Utility

A low-level C++ systems utility designed for secure remote server orchestration via POSIX APIs. 

### 📚 Currently Researching (Current Focus)

* **Kernel Space Internals (Ring 0):** Analyzing Windows I/O Request Packets (IRP), driver dispatchers, and memory management models (Paged vs Non-Paged Pools).
* **Vulnerability Mechanics:** Studying the root causes of memory corruption (Use-After-Free, Double Free, Race Conditions) and auditing data transfer methods (METHOD_NEITHER, METHOD_BUFFERED).
* **OS Security Controls:** Understanding hardware-assisted and software mitigations (SMEP/SMAP, KASLR math, Stack Canaries).
* **Hardware Virtualization Basics:** Conceptual architecture of Intel VMX (Root/Non-Root, VMCS, EPT mapping structures) in preparation for hypervisor development.

### 🎯 Architectural Goals & Roadmap

1. **Phase 1 (Kernel Practice):** Transition into hands-on kernel vulnerability discovery, master system-level debugging workflows under **WinDbg**, and build custom fuzzing tools.
2. **Phase 2 (Virtualization):** Design and implement a **custom, lightweight Type-2 Hypervisor** from scratch, directly configuring VMX states, VMCS layouts, and EPT paging structures.
3. **Phase 3 (Operating System):** Build a **custom, security-hardened x86-64 Operating System** from the ground up (custom bootloader, physical/virtual memory management subsystem, and a race-condition-free task scheduler).

### 🤝 Connect

Interested in hardware architecture, systems software engineering, kernel research, or low-level binary analysis? Let's talk code. 

**Telegram:** [@NeroMind](https://t.me/NeroMind)
