# Subject: Advanced Operating System (CS-601)

---

## Week 1

### 1. **Introduction to Operating System (OS)**

- **Definition**

  - An **Operating System (OS)** is a system software that manages hardware and software resources of a computer system and provides services for computer programs.
  - It acts as an **intermediary** between the **user** and **hardware**.

- **Why We Study OS**

  - To understand **resource management** (CPU, memory, I/O devices).
  - To learn **process synchronization**, **scheduling**, and **deadlock handling**.
  - To explore **modern OS concepts** like **distributed computing**, **virtualization**, and **cloud systems**.

- **Major Areas in OS**

  - **Process Management** → Handles creation, scheduling, and termination of processes.
  - **Memory Management** → Allocates and tracks system memory to ensure efficient usage.
  - **File System Management** → Organizes data into files and directories for easy access.
  - **I/O System Management** → Manages input/output operations and device communication.
  - **Security and Protection** → Protects data, resources, and users from unauthorized access.
  - **Networking and Communication** → Enables data exchange between systems via network protocols.

- **OS Manages**
  - **CPU** → Execution, Scheduling, ALU operations, Process Control.
  - **Memory** → Allocation, Paging, Segmentation, Virtual Memory.
  - **I/O Devices** → Disk, Keyboard, Mouse, Printers, Network Interfaces.
  - **Files** → Access control, Storage organization, File systems.

---

### 2. **Types & Structure of OS**

- **Types of Computing Systems**

  - **Cloud Computing** → Services delivered over the internet.
  - **Distributed Systems** → Multiple systems working as a single system.
  - **Embedded Systems** → OS designed for specific devices.
  - **Real-time Systems** → OS with strict timing constraints.

- **Key Concepts**

  - **Job** → A unit of work submitted to the OS.
  - **Process** → A running program in execution.
  - **Thread** → A lightweight process within a process.
  - **Scheduling** → Deciding which process runs next.
  - **Deadlock** → Situation where processes wait indefinitely for resources.
  - **Paging** → Memory management scheme eliminating contiguous allocation.

- **OS Concepts**

  - **Virtualization** → Creates virtual versions of hardware or OS to run multiple systems on one machine.
  - **Synchronization** → Ensures proper timing and coordination among concurrent processes.
  - **System Calls** → Interface allowing user applications to request OS services.
  - **Protection and Security** → Safeguards resources and maintains system integrity against threats.
  - **Concurrency Control** → Manages simultaneous execution to prevent race conditions and deadlocks.

### 3. **Computer System Organization**

- **Components**
  - **Hardware** → CPU, Memory, I/O Devices.
  - **Operating System** → Controls and coordinates hardware usage.
  - **Application Programs** → Compilers, Databases, Games, etc.
  - **Users** → Humans, other systems, or automated scripts.

---

## Week 2

### 1. **Memory Concepts**

- **Shared Memory** → Multiple processes access the same memory segment.
- **Main Memory** → Primary storage used during program execution.
- **Cache Memory** → High-speed memory for temporary data storage.
- **Registers** → Small, fastest storage inside the CPU.
- **Producer & Consumer Problem** → Synchronization example in shared memory.
- **Message Passing** → Communication between processes via messages.
- **Sockets** → Network communication endpoints for data exchange.

---

### 2. **Management Definitions**

- **Memory Management** → Allocating, tracking, and protecting memory spaces.
- **File Management** → Organizing, storing, and accessing data in files.
- **Mass Storage Management** → Handling data storage devices like HDD/SSD.
- **Cache & Register Management** → Optimizing data access speed.
- **TCP/IP Management** → Managing network communication protocols.

#### Network Types

- **LAN (Local Area Network)** → Small, local network (office, campus).
- **WAN (Wide Area Network)** → Large geographical area (internet).
- **MAN (Metropolitan Area Network)** → City-wide network.
- **PAN (Personal Area Network)** → Devices close to a person (Bluetooth).
- **SAN (Storage Area Network)** → High-speed network for storage systems.

---

### 3. **System Architecture**

- **Computing Environments**

  - **Traditional Computing** → Desktop and personal systems.
  - **Mobile Computing** → Smartphones and tablets.
  - **Peer-to-Peer (P2P)** → Equal nodes sharing resources.
  - **Client-Server** → Clients request services from servers.
  - **Cloud Computing** → Scalable services via internet.

- **Kernel Data Structures**

  - **Process Table** → Stores information about each active process (state, PID, registers).
  - **File Table** → Keeps records of open files and their attributes.
  - **Memory Map** → Tracks allocation of memory spaces to processes and devices.
  - **I/O Queue** → Maintains list of pending I/O operations for scheduling.
  - **System Call Interface** → Acts as a bridge between user programs and kernel functions.

---

### 4. **Research & Assignment Section**

#### **Ideas: AI/ML Integration with OS (Examples)**

- AI-based process scheduling.
- ML for resource prediction and optimization.
- Anomaly detection in system logs.
- Self-healing OS components.
- Adaptive energy management using ML.

#### **Research Paper Types**

- **General Paper** → Discusses common or broad concepts.
- **Book Chapter** → Detailed, conceptual, often review-based.
- **Conference Paper** → Short and recent research findings.
- **Survey Paper** → Summarizes multiple related research works.

#### **Paper Categories**

- **W** → Weak (basic idea, poor validation)
- **X** → Moderate (standard contribution)
- **Y** → Strong (validated research, solid results)
- **Z** → Excellent (novel contribution, high impact)

- **Impact Factor (IF)** → Measure of journal’s influence (citations per paper).

---

### 5. **Paper Components and Guidelines**

#### **Main Components**

- **Title** → Concise and descriptive.
- **Authors** → Contributors’ names and affiliations.
- **Abstract** → Summary (150–250 words).
- **Keywords** → 4–6 important terms.

#### **Sections**

1. **Introduction** → Problem statement and motivation.
2. **Related Work** → Previous studies and research gaps.
3. **Proposed Work** → Your idea, model, or algorithm.
4. **Limitations** → Weak points or future improvements.
5. **Conclusion & Future Work** → Summary and next steps.
6. **References** → Proper citation format (IEEE / APA / Springer).

#### **Formatting Instructions**

- Avoid **Spelling & Grammar** mistakes.
- Maintain **Proper Alignments** and **Spacing**.
- Include **Figures**, **Tables**, and **Graphs**.
- Use **Pseudocode** for algorithms.
- Ensure **Architectural Diagrams** are labeled.
- **Paragraph length:** 4–5 lines max.
- **IEEE Format:** 6 pages limit.
- **Springer Format:** 10 pages limit.

## 🧠 Bonus Study Guide

- **Focus Topics for Exam**

  - Process Management (Scheduling, Deadlocks, Synchronization)
  - Memory Management (Paging, Segmentation, Virtual Memory)
  - File System & I/O Management
  - Distributed & Cloud Operating Systems
  - Kernel Structures and System Calls

- **Recommended Books**

  - _Operating System Concepts_ by Silberschatz, Galvin, Gagne
  - _Modern Operating Systems_ by Andrew S. Tanenbaum

- **Tips**
  - Use **diagrams** for architecture and process scheduling.
  - Practice **deadlock detection algorithms**.
  - Revise **paging and segmentation** numerical.
  - Read at least one **research paper** on modern OS trends (e.g., AI integration).

---

## w3

- Class miss

<!--
. **Topic**
   - SubTopics
   - SubTopics
   - SubTopics
 -->

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
