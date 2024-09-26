

Prepare for 

Mr. Mony Soeurn

Lecturer (OS) Operating System

Information Technology Engineering

By Pun VireakRoth


pun.vireakroth.2821\@rupp.edu.kh 

Information Technology Engineering



25th September 2024


# Table of Contents

[OPERATING SYSTEM CONCEPTS by ABRAHAM SILBERSCHATZ](#operating-system-concepts-by-abraham-silberschatz)

[Chapter 1: Introduction](#chapter-1-introduction)

[1.1 What Operating Systems Do](#11-what-operating-systems-do)

[1.2 Computer-System Organization](#12-computer-system-organization)

[1.3 Computer-System Architecture](#13-computer-system-architecture)

[1.4 Operating-System Operations](#14-operating-system-operations)

[1.5 Resource Management](#15-resource-management)

[1.6 Security and Protection](#16-security-and-protection)

[1.7 Virtualization](#17-virtualization)

[1.8 Distributed Systems](#18-distributed-systems)

[1.9 Kernel Data Structures](#19-kernel-data-structures)

[1.10 Computing Environments](#110-computing-environments)

[1.11 Free and Open-Source Operating Systems](#111-free-and-open-source-operating-systems)

[MODERN OPERATING S YSTEMS FOURTH EDITION by ANDREW S. TANENBAUM HERBERT BOS](#modern-operating-s-ystems-fourth-edition-by-andrew-s-tanenbaum-herbert-bos)

[Chapter 1: Introduction](#chapter-1-introduction-1)

[1.1 What is an Operating System?](#11-what-is-an-operating-system)

[1.2 History of Operating Systems](#12-history-of-operating-systems)

[1.3 Computer Hardware Review](#13-computer-hardware-review)

[1.4 The Operating System Zoo](#14-the-operating-system-zoo)

[1.5 Operating System Concepts](#15-operating-system-concepts)

[1.6 System Calls](#16-system-calls)

[1.7 Operating System Structure](#17-operating-system-structure)

[1.8 The World According to C](#18-the-world-according-to-c)

[Operating Systems: Internals and Design Principles (Sixth Edition) by William Stallings](#operating-systems-internals-and-design-principles-sixth-editioniamaspaceby-william-stallings)

[Chapter 1: Introduction](#chapter-1-introduction-2)

[1.1 Basic Elements](#11-basic-elements)

[1.2 Processor Registers](#12-processor-registers)

[1.3 Instruction Execution](#13-instruction-execution)

[1.4 Interrupts](#14-interrupts)

[1.5 The Memory Hierarchy](#15-the-memory-hierarchy)

[1.6 Cache Memory](#16-cache-memory)

[1.7 I/O Communication Techniques](#17-io-communication-techniques)


# OPERATING SYSTEM CONCEPTS by _ABRAHAM SILBERSCHATZ_

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeZXANR4v0thbyFq5gNOX-CXACXstBAYbmz5jzpHxb7fA-h2uQxuH0Tnhb-Ml5YKLS1i8RlH5lC7obypsVNoGlh0SgGnOFIE3OfKTNc5FLaxGgX5HbSVdPPd6KyN-US6M1iT8FPhYPewF7rjUd9toQmEEs?key=M1_GJRJoRGvIPPkB8SbJCA)


### **Chapter 1: Introduction** 

### **1.1 What Operating Systems Do**

Operating systems act as connections between users and hardware, managing resources like memory, CPU, and storage. They ensure the computer runs efficiently while providing a user-friendly environment.


#### **1.2 Computer-System Organization**

A computer consists of hardware components like the CPU, memory, and input/output devices. Operating systems manage the communication between these components and respond to hardware events through interrupts.


#### **1.3 Computer-System Architecture**

Single-processor and multi-processor systems form the basic types of computer architectures. Clustered systems consist of multiple computers working together to improve reliability and performance.


#### **1.4 Operating-System Operations**

Operating systems manage multiple tasks simultaneously through multiprogramming, switching between processes efficiently. They operate in two modes—user mode for regular tasks and kernel mode for system-level functions, ensuring security and control.


#### **1.5 Resource Management**

Operating systems allocate resources such as CPU, memory, and storage to different programs and users. Time-sharing is a method where multiple processes share CPU time, making resource allocation fair and efficient.


#### **1.6 Security and Protection**

Operating systems implement protection mechanisms to control access to resources and enforce security by preventing unauthorized access and ensuring data safety.


#### **1.7 Virtualization**

Virtualization allows multiple virtual machines (VMs) to run on one physical machine, creating flexible and efficient environments for running different operating systems simultaneously.


#### **1.8 Distributed Systems**

In distributed systems, multiple computers work together, sharing resources and improving performance. These systems rely on networks to function as a single, cohesive unit.


#### **1.9 Kernel Data Structures**

Operating systems use data structures like lists, stacks, and queues within the kernel to manage processes, memory, and devices efficiently.


#### **1.10 Computing Environments**

Different computing environments include traditional desktops, mobile devices, client-server systems, peer-to-peer networks, and cloud computing. Operating systems must adapt to these environments to meet the specific needs of users and systems.


#### **1.11 Free and Open-Source Operating Systems**

Free and open-source operating systems, such as Linux, allow users to modify and share code. These systems are widely used in servers and academic settings, promoting innovation and collaboration.


# MODERN OPERATING S YSTEMS FOURTH EDITION _by ANDREW S. TANENBAUM HERBERT BOS_

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcEuFnfq4MnlaDx__0C_jVLAQp4N1XmWCQ79drjD1LcPJ9q-ZGt6zOhb67G2E-B8OSWriSso_c-2Yt6FBM_rnnSYFcoSJAQdKw8A8XWU2nSURHBs2cdSPmlnvjWAkD_CdO8jdSrqjMR8mrI-TjFRZitEwPD?key=M1_GJRJoRGvIPPkB8SbJCA)


### **Chapter 1: Introduction** 

#### **1.1 What is an Operating System?**

An operating system (OS) is software that manages hardware resources and provides services to users and applications. It acts as an intermediary between users and hardware, ensuring efficient resource allocation and task management.


#### **1.2 History of Operating Systems**

Operating systems have evolved through several phases:

- **Batch Systems**: Early computers ran one job at a time with no user interaction.

- **Multiprogramming**: Introduced to run multiple jobs simultaneously by switching between them.

- **Time-Sharing Systems**: Allowed multiple users to interact with the computer at the same time.

- **Personal Computers**: OS designs adapted to single-user, interactive environments with the rise of personal computing.

- **Distributed and Networked Systems**: Modern systems expanded to include networking, allowing computers to communicate and share resources over networks.


#### **1.3 Computer Hardware Review**

A brief overview of the hardware components managed by the OS:

- **Processors (CPUs)**: Execute instructions.

- **Memory (RAM)**: Temporarily stores data for running programs.

- **I/O Devices**: Input and output devices such as keyboards, screens, and disks.

- **Buses**: Communication paths that connect different parts of the computer.


#### **1.4 The Operating System Zoo**

Various types of operating systems:

- **Mainframe OS**: Designed for large, powerful computers used in enterprises.

- **Server OS**: Handles the needs of server machines, supporting multiple users and heavy I/O demands.

- **Multiprocessor OS**: Supports systems with more than one CPU.

- **Personal Computer OS**: Found in desktops and laptops.

- **Real-Time OS**: Systems where timing is critical, used in embedded systems.

- **Embedded OS**: Small, highly specialized systems for devices like smartphones, appliances, and cars.


#### **1.5 Operating System Concepts**

Key OS concepts:

- **Processes**: A process is a running program, and the OS manages multiple processes.

- **Address Spaces**: The OS controls the memory each process can access.

- **Files**: The OS manages files stored on disks.

- **Input/Output**: Operating systems manage the communication between devices and the computer.

- **System Calls**: Special operations where user programs request services from the OS.


#### **1.6 System Calls**

System calls are how programs request services from the OS, such as reading files, writing data, or creating new processes. This part explains how system calls work and why they are important for allowing user programs to interact with hardware.


#### **1.7 Operating System Structure**

Operating systems can be designed in different ways:

- **Monolithic Systems**: A single large program containing all OS functions.

- **Layered Systems**: Organized in layers where each layer uses the functions of the one below it.

- **Microkernels**: A minimal core OS that provides basic services, while other components run in user space.


#### **1.8 The World According to C**

C programming language plays a significant role in operating system development. Most operating systems are written in C because it provides low-level hardware control while allowing structured programming.


# _Operating Systems: Internals and Design Principles (Sixth Edition)_ _by William Stallings_

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfNuDgl660QU3PLTF-ORuyVaxuKlZSDqX0xChnmavFPBrX1-QkEUs7_KKEb7OjZrA3AmjzHP97Xf0c2agsDsaNe4NLIkJoWyj-iQqWRc6kxTrV6MtEmqhqvFFgPlOezTJPL_AyfMrotwGtOTrGnq4cZhlTz?key=M1_GJRJoRGvIPPkB8SbJCA)


### **Chapter 1: Introduction** 

### **1.1 Basic Elements**

A computer system is made up of key components like the processor, memory, I/O devices, and the system bus. The processor executes instructions, memory stores data and programs, I/O devices handle interactions with the outside world, and the system bus connects everything together for communication.


#### **1.2 Processor Registers**

Processor registers are small, high-speed storage areas inside the CPU. They temporarily hold data that's needed while executing instructions. Important registers include the program counter (which keeps track of the next instruction), the instruction register (which holds the current instruction), and general-purpose registers for holding data during computation.


#### **1.3 Instruction Execution**

Instruction execution follows a cycle where the CPU fetches an instruction from memory, decodes it to figure out what it needs to do, and then executes it. This process—fetch, decode, execute—repeats continuously and is the core of how the CPU processes programs. Each step involves accessing memory, updating registers, and possibly interacting with I/O devices.


#### **1.4 Interrupts**

Interrupts allow the CPU to respond to urgent events, like input from a keyboard or the completion of an I/O operation. Instead of the CPU sitting idle waiting for something to happen, interrupts tell it to stop what it’s doing and handle the new event immediately. The CPU then goes back to what it was doing after the interrupt is processed. This mechanism greatly improves system efficiency.


#### **1.5 The Memory Hierarchy**

In a computer, memory is organized into a hierarchy based on speed and size. At the top is the fastest but smallest memory, like CPU cache, followed by main memory (RAM), and finally secondary storage like hard drives, which are slower but hold more data. The system makes use of faster memory for frequently accessed data, improving performance.


#### **1.6 Cache Memory**

Cache memory sits between the CPU and main memory and speeds up access to frequently used data. Since programs tend to use the same data repeatedly, caching improves performance by reducing the need to access slower main memory. The closer and faster the memory is to the CPU, the quicker programs can execute.


#### **1.7 I/O Communication Techniques**

There are different methods for handling input and output (I/O) operations:

- **Programmed I/O**: The CPU controls all data transfers, but this method can be inefficient since the CPU has to wait for the I/O to complete.

- **Interrupt-driven I/O**: The CPU starts the I/O operation, moves on to other tasks, and gets interrupted when the I/O operation finishes.

- **Direct Memory Access (DMA)**: A special controller handles the data transfer between memory and I/O devices directly, freeing up the CPU to focus on other tasks without needing to micromanage I/O operations.
