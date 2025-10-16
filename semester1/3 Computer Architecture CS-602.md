# Subject: 3 Computer Architecture CS-602

## week1

1. **Intro & Basic Concepts**

   - **What is Computer Architecture**
     - Structure and behavior of a computer as seen by the programmer.
     - Defines instruction set, addressing modes, and data formats.

   - **Why we study Computer Architecture**
     - To understand how hardware executes software efficiently.
     - Helps in performance tuning, troubleshooting, and system design.

   - **What we study in Computer Architecture**
     - CPU structure, memory hierarchy, I/O systems, instruction cycles, and system buses.

   - **Difference between Architecture & Organization**
     - _Architecture_: Logical design (instruction set, addressing, etc.)
     - _Organization_: Physical implementation (hardware circuits, control signals)

   - **Compiler**
     - Converts high-level code to machine language.

   - **Assembler**
     - Converts assembly code to machine language.

2. **Instruction Cycle**

   - Cycle
     - **Fetch Cycle** – CPU fetches instruction from memory (PC → MAR → Memory → IR)
     - **Execute Cycle** – CPU decodes and performs the operation.
   - **Registers**

     - **PC** – Program Counter: holds address of next instruction.
     - **IR** – Instruction Register: holds current instruction.
     - **MAR** – Memory Address Register: holds address for memory access.
     - **MBR** – Memory Buffer Register: holds data being transferred.
     - **I/OAR** – I/O Address Register: holds I/O device address.
     - **I/OBR** – I/O Buffer Register: holds I/O data temporarily.

   - **Address Calculation**

     - **Fetch Instruction** – Retrieve from memory using PC.
     - **Decode** – Identify opcode and operands.
     - **Opcode** – Specifies operation type.
     - **Effective Address** – Calculated if operand in memory.
     - **Execute** – Perform the operation and store result.

   - **Program Flow**
     - **Without Interrupts** – Executes instructions sequentially.
     - **With Interrupts** – CPU temporarily halts program to handle event, then resumes.

3. **System Bus**

   - **Data Bus**
     - Carries actual data between CPU, memory, and I/O devices.

   - **Address Bus**
     - Carries memory or device address (unidirectional from CPU).

   - **Control Bus**
     - Carries control signals like Read/Write, Interrupt, and Clock.

   - **Elements of Bus Design**
     - **Type** – Dedicated, Multiplexed, or Shared.
     - **Bus Width** – Number of lines; defines how much data can transfer at once.
     - **Data Transfer** – Synchronous or Asynchronous communication mode.

---

## week2

1. **Methods**

   - **Centralized Synchronous**

     - All devices operate under a single clock control.
     - Predictable timing but less flexible.

   - **Distributed Asynchronous**

     - No global clock; devices communicate via handshake signals.
     - More flexible but complex.

   - **Timing**
     - **Synchronous** – All operations follow master clock.
     - **Asynchronous** – Operations depend on completion of previous event, not clock.

2. **Assignment - Chapter 3**

   - **p1** – Decode given instructions and show in binary form.
   - **p2** – 32-bit system:
     - Instruction size = 32 bits.
     - First bits = opcode.
     - Remaining 24 bits = operand address.
     - IR (Instruction Register) = 32 bits.
   - **p..** – Will add later.

   > **ToDo** _Assignment Tip:_ Practice binary decoding, opcode separation, and address calculation.

3. **Cache Memory**

   - **Locations**
     - Between CPU and Main Memory (Level 1, 2, 3 caches).

   - **Capacity**
     - Small but very fast memory (64KB–8MB).

   - **Access**
     - Faster than main memory, used to store frequently used data.

   - **Performance**
     - Measured using _Hit Ratio_:
       - Hit Ratio = Cache Hits / (Cache Hits + Cache Misses)
       - Higher ratio → Better performance.

   - **Physical Type**
     - Uses _Static RAM (SRAM)_ – faster than DRAM used in main memory.

   - **Organization**
     - **Direct Mapping** – Each block maps to one fixed cache line.
     - **Associative Mapping** – Block can go anywhere in cache.
     - **Set-Associative Mapping** – Combination of both methods.

   - **How Data Transfers**
     - **Memory → Cache → CPU** – CPU first checks cache for data.
     - **CPU → Memory** – Data written through cache (write-back or write-through policies).

---

### Guide

- Focus on **Instruction Cycle**, **Registers**, and **Cache Mapping Types**.
- Understand **Synchronous vs Asynchronous** timing differences.
- Prepare short notes and diagrams (Instruction Cycle, System Bus, Cache Flow).
- Expected short questions: definitions, register roles, and cache hit ratio formula.

---

## w3

- **Class Miss**

---

## w4

1. **Topic 1**
   - SubTopics
2. **Topic 2**
   - SubTopics

<!--
. **Topic**
   - SubTopics
   - SubTopics
   - SubTopics
 -->
