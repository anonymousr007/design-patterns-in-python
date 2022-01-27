# RISC-V


- Chapter 1 Computer Abstractions and Technology
  - 1.1 Introduction
  - 1.2 Eight Great Ideas in Computer Architecture
  - 1.3 Below Your Program
  - 1.4 Under the Covers
  - 1.5 Technologies for Building Processors and Memory
  - 1.6 Performance
  - 1.7 The Power Wall
  - 1.8 The Sea Change: The Switch from Uniprocessors to Multiprocessors
  - 1.9 Real Stuff: Manufacturing and Benchmarking the AMD Barcelona
  - 1.10 Fallacies and Pitfalls
  - 1.11 Concluding Remarks
  - 1.12 Historical Perspective and Further Reading
  - 1.13 Exercises
- Chapter 2 Instructions: Language of the Computer
  - 2.1 Introduction
  - 2.2 Operations of the Computer Hardware
  - 2.3 Operands of the Computer Hardware
  - 2.4 Signed and Unsigned Numbers
  - 2.5 Representing Instructions in the Computer
  - 2.6 Logical Operations
  - 2.7 Instructions for Making Decisions
  - 2.8 Supporting Procedures in Computer Hardware
  - 2.9 Communicating with People
  - 2.10 RISC-V Addressing for Wide Immediates and Addresses
  - 2.11 Parallelism and Instructions: Synchronization
  - 2.12 Translating and Starting a Program
  - 2.13 A C Sort Example to Put It All Together
  - 2.14 Arrays versus Pointers
  - 2.15 Advanced Material: Compiling C and Interpreting Java
  - 2.16 Real Stuff: MIPS Instructions
  - 2.17 Real Stuff: x86 Instructions
  - 2.18 Real Stuff: The Rest of the RISC-V Instruction Set
  - 2.19 Concluding Remarks
  - 2.20 Historical Perspective and Further Reading
  - 2.21 Exercises
- Chapter 3 Arithmetic for Computers
  - 3.1 Introduction
  - 3.2 Addition and Subtraction
  - 3.3 Multiplication
  - 3.4 Division
  - 3.5 Floating Point
  - 3.6 Parallelism and Computer Arithmetic: Subword Parallelism
  - 3.7 Real Stuff: Streaming SIMD Extensions and Advanced Vector Extensions in x86
  - 3.8 Goinf Faster: Subword Parallelism and Matrix Multiply
  - 3.8 Fallacies and Pitfalls
  - 3.9 Concluding Remarks
  - 3.10 Historical Perspective and Further Reading
  - 3.11 Exercises
- Chapter 4 The Processor
  - 4.1 Introduction
  - 4.2 Logic Design Conventions
  - 4.3 Building a Datapath
  - 4.4 A Simple Implementation Scheme
  - 4.5 An Overview of Pipelining
  - 4.6 Pipelined Datapath and Control
  - 4.7 Data Hazards: Forwarding versus Stalling
  - 4.8 Control Hazards
  - 4.9 Exceptions
  - 4.10 Parallelism via Instructions
  - 4.11 Real Stuff: The ARM Cortex-A53 and Intel Core i7 Pipelines
  - 4.12 Going Faster: Instructio-Level Parallelism and Matrix Multiply
  - 4.13 Advanced Topic: An Introduction to Digital Design Using a Hardware Design Language to Describe and Model a Pipeline and More Pipelining Illustrations
  - 4.13 Fallacies and Pitfalls
  - 4.14 Concluding Remarks
  - 4.15 Historical Perspective and Further Reading
  - 4.16 Exercises
- Chapter 5 Large and Fast: Exploiting Memory Hierarchy
  - 5.1 Introduction
  - 5.2 Memory Technologies
  - 5.3 The Basics of Caches
  - 5.4 Measuring and Improving Cache Performance
5.4 Virtual Memory
5.5 A Common Framework for Memory Hierarchies 406
5.6 Virtual Machines 413
5.7 Using a Finite State Machine to Control A Simple Cache 417
5.8 Parallelism and Memory Hierarchies: Cache Coherence 422
5.9 Advanced Material: Implementing Cache Controllers 426
5.10 Real Stuff: The AMD Opteron x4 (Barcelona) and Intel Nehalem Memory
Hierarchies 427
5.11 Fallacies and Pitfalls 431
5.12 Concluding Remarks 435
5.13 Historical Perspective and Further Reading 436
5.14 Exercises 436
Chapter 6 Storage and Other I/O Topics
6.1 Introduction 438
6.2 Dependability, Reliability, and Availability 441
6.3 Disk Storage 443
6.4 Flash Storage 448
6.5 Connecting Processors, Memory, and I/O Devices 450
6.6 Interfacing I/O Devices to the Processor, Memory, and Operating
System 454
6.7 I/O Performance Measures: Examples from Disk and File Systems 464
6.8 Designing an I/O System 466
6.9 Parallelism and I/O: Redundant Arrays of Inexpensive Disks 467
6.10 Real Stuff: Sun Fire x4150 Server 474
6.11 Advanced Topics: Networks 480
6.12 Fallacies and Pitfalls 480
6.13 Concluding Remarks 485
6.14 Historical Perspective and Further Reading 486
6.15 Exercises 486
Chapter 7 Multicores, Multiprocessors, and Clusters
7.1 Introduction 488
7.2 The Difficulty of Creating Parallel-Processing Programs 490
7.3 Shared Memory Multiprocessors 494
7.4 Clusters and Other Message-Passing Multiprocessors 497
7.5 Hardware Multithreading 501
7.6 SISD, MIMD, SIMD, SPMD, and Vector 504
7.7 Introduction to Graphics Processing Units 510
7.8 Introduction to Multiprocessor Network Topologies 514
7.9 Multiprocessor Benchmarks 518
7.10 Roofline: A Simple Performance Model 521
7.11 Real Stuff: Benchmarking Four Multicores Using the Roofline Model 529
7.12 Fallacies and Pitfalls 538
7.13 Concluding Remarks 540
7.14 Historical Perspective and Further Reading 542
7.15 Exercises 542 
Appendix A Graphics and Computing GPUs 
A.1 Introduction 
A.2 GPU System Architectures 
A.3 Scalable Parallelism ¿ Programming GPUs 
A.4 Multithreaded Multiprocessor Architecture 
A.5 Parallel Memory System G.6 Floating Point 
A.7 Real Stuff: The NVIDIA GeForce 8800 
A.8 Real Stuff: Mapping Applications to GPUs
A.9 Fallacies and Pitfalls 
A.10 Concluding Remarks 
A.11 Historical Perspective and Further Reading
Appendix B Applications, Linkers, and the SPIM Simulator
B.1 Introduction A-3
B.2 Assemblers A-10
B.3 Linkers A-18
B.4 Loading A-19
B.5 Memory Usage A-20
B.6 Procedure Call Convention A-22
B.7 Exceptions and Interrupts A-34
B.8 Input and Output A-38
B.9 SPIM A-42
B.10 MIPS R2000 Assembly Language A-46
B.11 Concluding Remarks A-82
B.12 Exercises A-83
CD-ROM Content
Appendix C The Basics of Logic Design
C.1 Introduction B-3
C.2 Gates, Truth Tables, and Logic Equations B-4
C.3 Combinational Logic B-8
C.4 Using a Hardware Description Language B-20
C.5 Constructing a Basic Arithmetic Logic Unit B-26
C.6 Faster Addition: Carry Lookahead B-38
C.7 Clocks B-47
C.8 Memory Elements: Flip-Flops, Latches, and Registers B-49
C.9 Memory Elements: SRAMs and DRAMs B-57
C.10 Finite-State Machines B-67
C.11 Timing Methodologies B-72
C.12 Field Programmable Devices B-77
C.13 Concluding Remarks B-79
C.14 Exercises B-79
Appendix D Mapping Control to Hardware
D.1 Introduction C-3 
D.2 Implementing Combinational Control Units C-4 
D.3 Implementing Finite-State Machine Control C-8 
D.4 Implementing the Next-State Function with a Sequencer C-22 
D.5 Translating a Microprogram to Hardware C-28 
D.6 Concluding Remarks C-32 
D.7 Exercises C-33 
Appendix E A Survey of RISC Architectures for Desktop, Server, and Embedded Computers
E.1 Introduction D-3
E.2 Addressing Modes and Instruction Formats D-5
E.3 Instructions: The MIPS Core Subset D-9
E.4 Instructions: Multimedia Extensions of the Desktop/Server RISCs D-16
E.5 Instructions: Digital Signal-Processing Extensions of the Embedded RISCs D-19
E.6 Instructions: Common Extensions to MIPS Core D-20
E.7 Instructions Unique to MIPS-64 D-25
E.8 Instructions Unique to Alpha D-27
E.9 Instructions Unique to SPARC v.9 D-29
E.10 Instructions Unique to PowerPC D-32
E.11 Instructions Unique to PA-RISC 2.0 D-34
E.12 Instructions Unique to ARM D-36
E.13 Instructions Unique to Thumb D-38
E.14 Instructions Unique to SuperH D-39
E.15 Instructions Unique to M32R D-40
E.16 Instructions Unique to MIPS-16 D-41
E.17 Concluding Remarks D-43
Index
Glossary
Further Reading
