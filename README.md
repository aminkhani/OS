<div align="center">
  <a href="https://www.linkedin.com/in/aminkhani-ai/" targert="_blacnk">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  <a href="mailto:aminkhani2010@gmail.com" targert="_blacnk">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail Badge"/>
  </a>
  <a href="https://t.me/aminkhani_ai" targert="_blacnk">
    <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Badge"/>
  </a>  
  <a href="https://www.instagram.com/aminkhani_ai/" targert="_blacnk">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram Badge"/>
  </a>
  <a href="https://github.com/aminkhani/" targert="_blacnk">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="Github Badge" />
  </a>
</div>
<br />
<div align="center">
  <h1 align="center">Operating System (OS) Tutorial</h1>
  <img src="Pic/operating_system.jpg">
  <p align="center"> 
    <br />
   <a href="https://github.com/aminkhani/OS/issues/new?assignees=&labels=bug&template=bug_report.yml&title=%5BBUG%5D%3A+">🐛Report Bug</a>
   .
   <a href="https://github.com/aminkhani/OS/issues/new?assignees=&labels=question&template=question.yml&title=%5BQUESTION%5D%3A+">❓Ask Question</a>
   .
  <a href="https://github.com/aminkhani/OS/issues/new?assignees=&labels=like&template=like.yml&title=%5BLIKE%5D%3A+">👍Like the repo</a>
  .
  <a href="https://github.com/aminkhani/OS/issues/new?assignees=&labels=unlike&template=unlike.yml&title=%5BUNLIKE%5D%3A+">👎Dislike the repo</a>
  </p>
  </p>
</div><br />

</div>

> **Note**
>
> 📣 You can help to improve this repo, by giving me a **⭐star⭐** and **❤️following me❤️**

<h1 id="top">Contents</h1>
<ul>
    <li><a href="#why_os">Why Study Operating Systems (OS)?</a></li>    
    <li><a href="#os_definition">OS Definition and Function</a></li>
    <li><a href="#structure_os">Structure of a Computer System</a></li>
    <li><a href="#os_do">What Does an OS Do?</a></li>
    <li><a href="#his_os">History of OS</a></li>
    <li><a href="#basics_os">Basics of OS</a>
      <ul>
        <li><a href="#transistor">Trasistor</a></li>
        <li><a href="#ic">IC</a></li>
        <li><a href="#processor">Processor</a></li>
        <li><a href="#cpu">CPU</a></li>
        <li><a href="#microprocessor">Microprocessor</a></li>
        <li><a href="#gpu">GPU</a></li>
        <li><a href="#memory">Memory</a></li>
      </ul>
    </li>
    <li><a href="#terminalogy">OS Terminology</a>
      <ul>
        <li><a href="#interrupt">Interrupt</a></li>
      </ul>
    </li>
    <li><a href="#type_os">Types of OS</a>
      <ul>
        <li><a href="#batch_os">Batch OS</a></li>
        <li><a href="#multi_os">Multiprogramming OS</a></li>
        <li><a href="#multipro_os">Multiprocessing OS</a></li>
        <li><a href="#multitask_os">Multitasking OS</a></li>
        <li><a href="#net_os">Network OS</a></li> 
        <li><a href="#realtime_os">Real Time OS</a></li>  
        <li><a href="#time_os">Time-Sharing OS</a></li>     
        <li><a href="#distributed_os">Distributed OS</a></li>     
      </ul>
    </li>
</ul>

<h1 id="why_os">Why Study Operating Systems?</h1>

- **Modern computer** consists of one or more **[processors](#3-processor)**, some **[main memory](#7-memory)**, **disks**, **printers**, a **keyboard**, a **mouse**, a **display**, **network interfaces**, and various other **input/output devices**. All in all, a **complex system**. If every application programmer had to understand how all these things work in detail, no code would ever get written. Furthermore, managing all these components and using them optimally is an **exceedingly challenging job**. For this reason, computers are equipped with a layer of **software** called the **operating system**.
<br>

- **Simply because**, as almost **all code runs on top of an operating system**, knowledge of **how operating systems work** is **crucial** to **proper**, **efficient**, **effective**, and **secure** **programming**. 
<br>

- Understanding the **fundamentals of operating systems**, how they drive computer hardware, and what they provide to applications is not only essential to those who program them but also highly useful to those who **write programs on them and use them**.

<div align="right"><a href="#top" targert="_blacnk"><img src="https://img.shields.io/badge/Back to up-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>

<h1 id="os_definition">Operating System Definition and Function</h1>

- In the **Computer System** (comprises of **Hardware** and **Software**), **Hardware** can only understand **machine code** (in the form of **0** and **1**) which doesn't make any sense to a naive user. We need a system which can act as an **intermediary** and manage all the **processes** and **resources** present in the system.
<br>
<img src="Pic/os-definition-and-functions.png">
<br>

- An **Operating System** can be defined as an **interface between user and hardware**. It is **responsible** for the **execution** of all the **processes**, **Resource Allocation**, **[CPU](#4-cpu-central-processing-unit) management**, **File Management** and many other tasks.
<br>

- The **purpose** of an operating system is to **provide an environment** in which a user can **execute programs** in **convenient and efficient manner**.

<div align="right"><a href="#top" targert="_blacnk"><img src="https://img.shields.io/badge/Back to up-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>

<h1 id="structure_os">Structure of a Computer System</h1>

- ### A Computer System consists of:
  - #### Users 
    - People who are using the computer.
  - #### Application Programs 
    - Compilers, Databases, Games, Video player, Browsers, etc.
  - #### System Programs 
    - Shells, Editors, Compilers, etc.
  - #### Operating System 
    - A special program which acts as an interface between user and hardware.
  - #### Hardware
    - CPU, Disks, Memory, I/O Devices ,etc.

<div align="right"><a href="#top" targert="_blacnk"><img src="https://img.shields.io/badge/Back to up-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>
<h1 id="os_do">What Does an Operating system Do?</h1>

#### 1. Process Management
#### 2. Process Synchronization
#### 3. Memory Management
#### 4. CPU Scheduling
#### 5. File Management
#### 6.Security

<div align="right"><a href="#top" targert="_blacnk"><img src="https://img.shields.io/badge/Back to up-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>

<h1 id="his_os">Operating Systems - History</h1>

- #### 1945 – 1955 : The First Generation, Vacuum Tubes and Plugboards

- #### 1955 – 1965 : The Second Generation, Transistors and Batch Systems

- #### 1965 - 1980 : The Third Generation, ICs and Multiprogramming
- #### 1980 - Present : The Fourth Generation, Personal Computers
- #### 1990 - Present : The Fifth Generation, Moblie Computets


<div align="right"><a href="https://github.com/aminkhani/OS/blob/main/history.md"><img src="https://img.shields.io/badge/Read More-green?style=for-the-badge">
<a href="#top" targert="_blacnk"><img src="https://img.shields.io/badge/Back to up-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>

<h1 id="basics_os">Basics of Operating System</h1>

- Some **basic knowledge of the structure of Computer System** is **required** to **understand how Operating System works**. 
<br>

- **Operating system** is intimately tied to the **hardware** of the computer it runs on. It **extends** the **computer’s instruction set** and **manages its resources**.
<br>
<img src="Pic/copmuter_hardware.jpg">
<br>

- The **CPU**, **memory**, and **I/O devices** are all connected by a **system bus** and communicate with one another over it

<span id="transistor"></span>

## 1. Transistor
- A **transistor** is a **[semiconductor device](https://en.wikipedia.org/wiki/Semiconductor_device)** used to **amplify** or **switch electrical signals** and **power**. 
<br>

- A **transistor** is a **binary switch** and the **fundamental building block** of **computer circuitry**.
  - The **transistor** either **prevents or allows** **current** to flow through.
<br>

- A **single modern CPU** can have **hundreds of millions** or even **billions** of **transistors**.

<div align="right">
<a href="https://en.wikipedia.org/wiki/Transistor"><img src="https://img.shields.io/badge/Read More-green?style=for-the-badge"></a>
<a href="#top"><img src="https://img.shields.io/badge/Back to up-orange?style=for-the-badge&logo=expo&logoColor=white"></a>
</div>

<span id="ic"></span>

## 2. Integrated Circuit (IC)
- An **integrated circuit** or **monolithic integrated circuit** (also referred to as an **IC**, a **chip**, or a **microchip**) is a **set of electronic circuits** on one **small flat piece** (or **chip**) of **semiconductor material**, usually **silicon**.
<br>

- On which **thousands or millions of tiny** **resistors**, **capacitors**, **diodes** and **transistors** are fabricated.

<div align="right">
<a href="https://en.wikipedia.org/wiki/Integrated_circuit"><img src="https://img.shields.io/badge/Read More-green?style=for-the-badge"></a>
<a href="#top"><img src="https://img.shields.io/badge/Back to up-orange?style=for-the-badge&logo=expo&logoColor=white"></a>
</div>

<span id="processor"></span>

## 3. Processor
- In **computing** and **computer science**, a **processor** or **processing unit** is an **electrical component (digital circuit)** that **performs operations** on an **external data source**, usually **memory** or some other data stream.
<br>

- It typically takes the form of a **microprocessor**. Today, processors use built-in transistors.
<br>

- Like a **soul in our body** keeps us alive so that the **processor** does in the computer.
- ### Moore's law:
  - **Moore's law**, named after **[Gordon Moore](https://en.wikipedia.org/wiki/Gordon_Moore)**, is the **observation** and **projection** via historical trend that the **number of transistors** in **integrated circuits (IC)**, and therefore processors by extension, **doubles every two years**. The progress of processors has followed Moore's law closely.

- ### Types of Processors:
  - **[CPU](#4-cpu-central-processing-unit)**
  - **[GPU](#6-graphics-processing-unit-gpu)**
  - **[TPU]()**
  - **[PPU]()**
  - **[SPE or SPU]()**

<div align="right">
<a href="https://en.wikipedia.org/wiki/Processor_(computing)"><img src="https://img.shields.io/badge/Read More-green?style=for-the-badge"></a>
<a href="#top"><img src="https://img.shields.io/badge/Back to up-orange?style=for-the-badge&logo=expo&logoColor=white"></a>
</div>

<span id="cpu"></span>

## 4. CPU (Central Processing Unit)
<img src="Pic/Processor.jpg"><br>

- A **processor** is any component that processes commands, reads, and writes data. A **CPU** is a **Central Processing Unit**, and the **main processor** in a computer.
  -  Many different computer components, like hard drives, have processors but the CPU is the most important processor in a computer and controls everything.
<br>

- **Central processing units (CPUs)** are the **primary processors** in most computers. They are designed to **handle a wide variety** of **general computing tasks** rather than only a few domain-specific tasks.
<br>

- The **CPU** is a **microprocessor**. The **microprocessor** is an **integrated circuit (IC)** that is **made up of millions of transistors**. However, not all **microprocessors are CPUs**. There are **NPUs**, **GPUs** and **APUs** that remove network, graphics or audio processing from the **CPU**. 
<br>

- The **brain** of the **computer** is the **CPU (Central Processing Unit)**. It **fetches instructions** from **memory** and **executes** them. 
  <br>

- The basic **cycle** of every **CPU** is to **fetch** the **first instruction** from **memory**, **decode** it to **determine its type and operands**, **execute** it, and then **fetch**, **decode**, and **execute subsequent instructions**.
  - The cycle is repeated **until** the **program finishes**. In this way, programs are **carried out**.
<br>

- All **CPUs contain** some **registers** inside to **hold key variables and temporary results**.
<br>

### CPU Structure
<img src="Pic/computer_architecture.jpg">

- #### Registers
  - **Registers** are parts of the **CPU** that can **store data**.
  <br>

  - **Registers** operate a little like **RAM**, but **can’t hold as much data as RAM can**, but they operate considerably **faster**.
  <br>

  - **Most Important Registers**
    - **Accumulator (AC)**
      - Stores the results of calculations
    <br>

    - **Program Counter (PC)**
      - Stores the **address in RAM** of the **next instruction** to be executed.
    <br>

    - **Instruction Register (IR)**
      - Stores the address in RAM of the instruction to be processed
    <br>

    - **Memory Address Register (MAR)**
      - Stores the address in RAM of the data to be processed
    <br>

    - **Memory Data/Buffer Register (MDR/MBR)**
      - Stores the data to be processed
    <br>

    - **I/O Address Register (I/O AR)**
      - Stores the address of the I/O device to be accessed
    <br>

    - **I/O Data/Buffer Register (I/O DR/BR)**
      - Stores the data to be processed
    <br>

- **ALU(Arithmetic Logic Unit)**
  - The **ALU is the core of the CPU**.
  <br>

  - **ALU** is responsible for performing **arithmetic** and **logical functions** or **operations**. It consists of two subsections, which are:
    1. **Arithmetic Section**
       - By **arithmetic operations**, we mean operations like **addition**, **subtraction**, **multiplication**, and **division**, and all these operation and functions are performed by **ALU**. Also, all the complex operations are done by making repetitive use of the mentioned operations by **ALU**.
    <br> 

    2. **Logic Section**
       - By **Logical operations**, we mean operations or functions like **selecting**, **comparing**, **matching**, and **merging** the data, and all these are performed by ALU. 
    <br> 

> **Note:** **CPU** may contain **more than one ALU and ALUs** can be used for maintaining timers that help run the computer system.
  
<br>

- **Control Unit (CU)**
  - The **control unit decodes** what each **instruction means**, and can then controls how the other components operate.
  <br>

  - when the control unit receives an instruction, which is just a **binary number**, it will then **signal what the ALU and memory** is supposed to do.
  <br>

- **Memory**
  - The **RAM stores** both the instructions that the computer needs to perform, and the data on which to perform it.
<br>


- **Buses**
  - All of these components are connected together by bundles of wires that are collectively known as buses. So there is a bus to carry data, another for addresses, and another for instructions.
<br>

- **Input and Output**
  - Additionally, a computer would usually have some input and output devices that can receive external data and then output the results of the calculation. This could be something as simple as a data connection, or something more complicated such as a keyboard and monitor.
  
> This method of putting together a computer is known as the **[Von Neumann](https://en.wikipedia.org/wiki/Von_Neumann_architecture)** Architecture. It was devised by John von Neumann in about 1945, well before any of the components that would be needed to produce it had actually been invented.


<div align="right">
<a href="https://en.wikipedia.org/wiki/Central_processing_unit"><img src="https://img.shields.io/badge/Read More-green?style=for-the-badge"></a>
<a href="#top"><img src="https://img.shields.io/badge/Back to up-orange?style=for-the-badge&logo=expo&logoColor=white"></a>
</div>
<span id="microprocessor"></span>

## 5. Microprocessor
<img src="Pic/Microprocessor.jpg"><br>

- A **microprocessor** is a **computer processor** where the **data processing logic** and **control** is included on a **single integrated circuit (IC)**, or a **small number of integrated circuits**.
<br>

- The **microprocessor** contains the **arithmetic**, **logic**, and **control circuitry** **required to perform the functions** of a **computer's central processing unit**.
<br>

- The **integrated circuit (IC)** is capable of **interpreting and executing program instructions** and performing arithmetic operations.
<br>

- **Microprocessor** is the **latest** form of **processor or CPU**. The microprocessor is a **single-chip circuit integrated** with **all qualities of CPU** with few new circuits. Its processing **speed is greater than CPU**. Today all latest **processor CPUs are a microprocessor**.

<div align="right">
<a href="https://en.wikipedia.org/wiki/Microprocessor"><img src="https://img.shields.io/badge/Read More-green?style=for-the-badge"></a>
<a href="#top"><img src="https://img.shields.io/badge/Back to up-orange?style=for-the-badge&logo=expo&logoColor=white"></a>
</div>

### Key Differences between Processor and Microprocessor

1. Processor or CPU is capable of performing all kinds of computing and arithmetic functions while microprocessor deals in BIOS & memory circuits in addition to performing all CPU functions.
<br>

2. Microprocessor functions are greater than the processor. In addition to processor qualities, some graphic processor units (GPU), sound cards and internet cards are also included in it.
<br>

3. Microprocessor is the latest and upgraded version of processor/CPU.
<br>

4. Although microprocessor is the latest and advanced technology but still the main processing function of the computer is controlled by the processor.
<br>

5. The new function of audio processing which helps in producing clear audio is stored in a sound card of the microprocessor which was previously not available in the processor.
<br>

6. Due to the addition of different processors on a microprocessor, its speed is slower than the processor.
<br>

7. CPUs/processors can be microprocessor but all microprocessors are not CPU.
<br>

8. CPU is the main part of the computer while the microprocessor is a simple chip on the motherboard.

<div align="right"><a href="#top" targert="_blacnk"><img src="https://img.shields.io/badge/Back to up-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>

<span id="gpu"></span>

## 6. Graphics Processing Unit (GPU)
- A **graphics processing unit (GPU)** is a **computer chip** that **renders graphics** and **images** by performing **rapid mathematical calculations**.
<br>

- In the early days of computing, the **central processing unit (CPU)** performed these calculations. As more **graphics-intensive applications** were developed, however, their demands put a strain on the **CPU** and **decreased performance**. **GPUs** were developed as a way to offload those tasks from CPUs and to improve the **rendering of 3D graphics**. 
<br>

- **GPUs** work by using a method called **parallel processing**, where multiple processors handle separate parts of the same task.
<br>

- GPUs are fairly similar to CPU architectures. However, CPUs are used to respond to and process the basic instructions that drive a computer, while GPUs are designed specifically to quickly render high-resolution images and video. Essentially, CPUs are responsible for interpreting most of a computer's commands, while GPUs focus on graphics rendering.
<br>

<div align="right">
<a href="https://en.wikipedia.org/wiki/Graphics_processing_unit"><img src="https://img.shields.io/badge/Read More-green?style=for-the-badge"></a>
<a href="#top"><img src="https://img.shields.io/badge/Back to up-orange?style=for-the-badge&logo=expo&logoColor=white"></a>
</div>
<span id="memory"></span>

## 7. Memory
  - **Memory** is the **electronic holding place** for the **instructions** and **data** a computer needs to reach quickly. It's where information is stored for immediate use. Memory is one of the basic functions of a computer, because without it, a computer would not be able to function properly. 
  <br>

  - There are technically **two types of computer memory**: **primary and secondary**. The term memory is used as a **synonym** for **primary memory** or as an abbreviation for a specific type of primary memory called **random access memory (RAM)**. This type of memory is located on microchips that are physically close to a computer's **microprocessor**.
  <br>

  - When a program is open, it is loaded from secondary memory to primary memory. Because there are different types of memory and storage, an example of this could be a program being moved from a solid-state drive (SSD) to RAM
  <br>

  - Memory is volatile, which means that data in memory is stored temporarily. Once a computing device is turned off, data stored in volatile memory will automatically be deleted. When a file is saved, it will be sent to secondary memory for storage that are non-volatile.
  <br>

  - The **memory system** is constructed as a **hierarchy of layers**.
  <br>
  <img src="Pic/memory.jpg">
  <br>

  - The **top layer** consists of the **registers internal** to the CPU. They are made of the same material as the CPU and are thus just **as fast as the CPU**. Consequently, there is no delay in accessing them. The storage capacity available in them is typically 32 × 32 bits on a 32-bit CPU and 64 × 64 bits on a 64-bit CPU. Less than 1 KB in both cases. Programs must manage the registers (i.e., decide what to keep in them) themselves, in software.
  <br>

  - **Cache memory**, which is mostly **controlled** by the **hardware**. **Main memory** is **divided up** into **cache lines**, typically **64 bytes**, with addresses 0 to 63 in cache line 0, 64 to 127 in cache line 1, and so on. The most heavily used cache lines are kept in a high-speed cache located inside or very close to the CPU. When the program needs to read a memory word, the cache hardware checks to see if the line needed is in the cache. If it is, called a **cache hit** and else, **cache miss**.
    - **Cache hits** normally take about **two clock cycles**.
   <br>

  - Cache memory is limited in size due to its high cost. Some machines have two or even three levels of cache, each one slower and bigger than the one before it. 
  <br>
  
  - **Types of Cache**
    - **Primary Cache** 
      - A primary cache is always located on the processor chip. This cache is small and its access time is comparable to that of processor registers.
    - **Secondary Cache** 
      - Secondary cache is placed between the primary cache and the rest of the memory. It is referred to as the level 2 (L2) cache. Often, the Level 2 cache is also housed on the processor chip.
  <br>

  - Main memory is the primary, internal workspace in the computer, commonly known as RAM (random access memory). Specifications such as 4GB, 8GB, 12GB and 16GB almost always refer to the capacity of RAM. In contrast, disk or solid state storage capacities in a computer are typically 128GB or 256GB and higher
  <br>

  - Magnetic storage or magnetic recording is the storage of data on a magnetized medium. Magnetic storage uses different patterns of magnetisation in a magnetizable material to store data and is a form of non-volatile memory. The information is accessed using one or more read/write heads
  <br>
  
<div align="right">
<a href="https://en.wikipedia.org/wiki/Memory"><img src="https://img.shields.io/badge/Read More-green?style=for-the-badge"></a>
<a href="#top"><img src="https://img.shields.io/badge/Back to up-orange?style=for-the-badge&logo=expo&logoColor=white"></a>
</div>

<h1 id="terminalogy">Operating System Terminology</h1>

<span id="interrupt"></span>

- ## Interrupts
  - An **interrupt** is a **signal** to the **processor** **emitted by hardware or software** indicating an **event** that needs **immediate attention**. Whenever an interrupt occurs, the **controller completes the execution** of the **current instruction** and starts the execution of an **Interrupt Service Routine (ISR)** or **Interrupt Handler**.

  - #### Classes of Interrupts
    - **Program**
      - **Generated** by some **condition** that occurs as a result of an instruction execution, such as **arithmetic overflow**, **division by zero**, **attempt to execute an illegal machine instruction**, or reference outside a user's **allowed memory space**.
    <br>

    - **Timer**
      - **Generated by a timer** within the **processor**. This allows the operating system to perform certain functions on a regular basis.

    <br>

    - **I/O**
      - **Generated by an I/O controller**, to signal normal completion of an operation or to signal a variety of error conditions.
    <br>

    - **Hardware Failure**  
      - **Generated by a failure** such as **power failure** or **memory parity error**.

<div align="right">
<a href="#top"><img src="https://img.shields.io/badge/Back to up-orange?style=for-the-badge&logo=expo&logoColor=white"></a>
</div>
<h1 id="type_os">Types of Operating Systems</h1>

- **Operating System** is a well-organized collection of programs that manages the computer hardware. It is a type of **system software** that is responsible for the smooth functioning of the computer system.
<br>
<img src="Pic/types-of-operating-system.png">
<br>
<div align="right"><a href="#top" targert="_blacnk"><img src="https://img.shields.io/badge/Back to up-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>
<h2 id="batch_os">Batch Operating System</h2>

- In the **1970s**, **Batch processing** was very popular. In this technique, **similar types of jobs** were **batched together** and executed in time.
<br>

- This type of **operating system** **does not interact with the computer directly**.
<br>
<img src="Pic/BatchOS.jpeg">
<br>

- In **Batch operating system**, **access** is given to **more than one person**; they submit their respective jobs to the system for the execution.
<br>

- The system put all of the jobs in a **queue** on the basis of **first come**, **first serve** and then executes the jobs **one by one**. The users collect their respective output when **all the jobs** get executed.
<br>

- The **purpose** of this operating system was mainly to **transfer control** from one job to another as soon as the job was completed.


<div align="right"><a href="#top" targert="_blacnk"><img src="https://img.shields.io/badge/Back to up-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>
<h2 id="multi_os">Multiprogramming Operating System</h2>

- A **Multiprogramming Operating System** **runs multiple programs** on a **single processor**.
<br>

- **Multiprogramming** is an **extension** to **batch processing** where the **CPU** is always **kept busy**. **Each process** needs two types of **system time**: 
  1. **CPU time**
  2. **I/O time**
<br>
<img src="Pic/multiprogramming.png">
<br>

- In a **multiprogramming environment**, when a process does its I/O, The CPU can start the execution of other processes. Therefore, **multiprogramming** **improves** the **efficiency** of the system.

<div align="right"><a href="#top" targert="_blacnk"><img src="https://img.shields.io/badge/Back to up-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>

<h2 id="multipro_os">Multiprocessing Operating System</h2>

- In **Multiprocessing**, **Parallel computing** is achieved. There are **more than one processors**   present in the system which can execute more than one process at the same time. This will increase the throughput of the system.
<br>
<img src="Pic/multiprocessing.jpg">
<br>
<img src="Pic/multiprocessing-operating-system2.png">
<br>
<img src="Pic/Symmetric-Multiprocessing-Vs-Asymmetric-Multiprocessing.jpg">
<br>
<div align="right"><a href="#top" targert="_blacnk"><img src="https://img.shields.io/badge/Back to up-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>
<h2 id="multitask_os">Multitasking Operating System</h2>

- The **multitasking operating system** is a **logical extension of a multiprogramming system** that enables **multiple programs** simultaneously. It allows a user to perform more than one computer task at the same time.
<br>

- While a **multiprogramming operating system** allows **more than one program** to **run** simultaneously using a **single CPU**, a **multitasking operating system** allows **multiple processes** or **tasks** to be **executed** at the same time utilizing multiple CPUs.
<br>
<img src="Pic/Multitasking-in-operating-system.png">
<br>
<img src="Pic/2.webp">
<br>
<img src="Pic/multitasking-operating-system2.png">
<br>

- In **preemptive multitasking**, the **operating system** can initiate a context **switching** from the running process to another process. In other words, the operating system **allows stopping the execution of the currently running process and allocating the CPU** to some other process.
<br>

- In **cooperative multitasking**, the operating system never initiates context switching from the running process to another process. A context switch occurs only when the processes voluntarily yield control periodically or when idle or logically blocked to allow multiple applications to execute simultaneously. Also, in this multitasking, all the processes cooperate for the scheduling scheme to work.


<div align="right"><a href="#top" targert="_blacnk"><img src="https://img.shields.io/badge/Back to up-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>
<h2 id="net_os">Network Operating Systems</h2>

- An **Operating system**, which includes **software** and **associated protocols** to communicate with **other computers** via a **network** conveniently and cost-effectively, is called **Network Operating System**.
<br>
<img src="Pic/network-operating-system2.png">
<br>

- In this type of operating system, **network traffic reduces** due to the **division between clients and the server**.
<br>

- This type of system is **less expensive** to **set up** and **maintain**.
<br>

- In this type of operating system, the **failure of any node** in a system affects the whole system.
<br>

- **Security and performance are important issues**. So trained network administrators are required for network administration.

<div align="right"><a href="#top" targert="_blacnk"><img src="https://img.shields.io/badge/Back to up-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>
<h2 id="realtime_os">Real Time Operating System</h2>

- In **Real-Time Systems**, each job **carries a certain deadline** within which the job is supposed to be **completed**, **otherwise**, the huge loss will be there, or even if the result is produced, it will be completely useless.
<br>
<img src="Piv/../Pic/real-time-operating-system.png">
<br>

- The **Application of a Real-Time system** exists in the case of **military applications**, if you want to drop a missile, then the missile is supposed to be dropped with a certain precision.
<br>
<img src="Pic/real-time-operating-system2.png">
<br>

- Easy to layout, develop and execute real-time applications under the real-time operating system.
<br>

- In a Real-time operating system, the maximum utilization of devices and systems.
<br>

- Real-time operating systems are very costly to develop.
<br>

- Real-time operating systems are very complex and can consume critical CPU cycles.
<div align="right"><a href="#top" targert="_blacnk"><img src="https://img.shields.io/badge/Back to up-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>

<h2 id="time_os">Time-Sharing Operating System</h2>

- In the **Time Sharing operating system**, computer resources are allocated in a time-dependent fashion to several programs simultaneously. Thus it helps to provide a large number of user's direct access to the main computer.
<br>

- It is a **logical extension of multiprogramming**. In time-sharing, the CPU is switched among multiple programs given by different users on a scheduled basis.
<br>

- A time-sharing operating system allows many users to be served simultaneously, so sophisticated CPU scheduling schemes and Input/output management are required.
<br>

- Time-sharing operating systems are very difficult and expensive to build.
<br>


- The time-sharing operating system provides effective utilization and sharing of resources.
<br>

- This system reduces CPU idle and response time.
<br>

- Data transmission rates are very high in comparison to other methods.
<br>

- Security and integrity of user programs loaded in memory and data need to be maintained as many users access the system at the same time.

<div align="right"><a href="#top" targert="_blacnk"><img src="https://img.shields.io/badge/Back to up-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>
<h2 id="distributed_os">Distributed Operating System</h2>

- The Distributed Operating system is not installed on a single machine, it is divided into parts, and these parts are loaded on different machines. A part of the distributed Operating system is installed on each machine to make their communication possible. Distributed Operating systems are much more complex, large, and sophisticated than Network operating systems because they also have to take care of varying networking protocols.
<br>

- The distributed operating system provides sharing of resources.
<br>

- This type of system is fault-tolerant.
<br>

- Protocol overhead can dominate computation cost.


<div align="right"><a href="#top" targert="_blacnk"><img src="https://img.shields.io/badge/Back to up-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>