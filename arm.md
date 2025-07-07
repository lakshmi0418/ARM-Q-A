#ARM INTERVIEW QUESTIONS

```c

what does arm stands for?
“ARM is a family of RISC (Reduced Instruction Set Computing) processor architectures originally named Acorn RISC Machine, later Advanced RISC Machines. It’s renowned for delivering high performance with very low power consumption, powering over 99% of premium smartphones today 

example:rosberipy,smartphone
what is arm processor?

An ARM processor is a RISC-based CPU architecture known for delivering strong performance with low power consumption and compact design

diff between risc and cisc?

RISC uses a small, fixed instruction set, optimizing for fast, single-cycle execution and hardware simplicity—ideal for mobile devices (like ARM in smartphones). 
CISC, exemplified by x86, provides a richer instruction set, allowing complex operations in fewer instructions, though each instruction takes longer and the hardware is more comple

arm architecture?
what are modes in arm?

ARM CPUs support multiple operating modes, each controlling privilege levels, register access, and exception handling, all managed by bits in the CPSR (Current Program Status Register)
keil.com+15s-o-c.org+15scribd.com+15
.
Modes Overview

    User (USR) – Unprivileged mode for regular applications. Cannot access protected system resources
    onlinedocs.microchip.com+3s-o-c.org+3boardor.com+3
    .

    System (SYS) – Privileged mode using the same registers as User mode, primarily for OS-level tasks
    riscos.com+10boardor.com+10fr.scribd.com+10
    .

    Supervisor (SVC) – OS kernel mode entered after reset or via SVC instruction (formerly SWI)
    twiserandom.com+11boardor.com+11scribd.com+11
    .

    FIQ – Fast interrupt mode with dedicated registers and higher priority for low-latency tasks
    en.wikipedia.org+14s-o-c.org+14fr.scribd.com+14
    .

    IRQ – General interrupt mode with banked stack pointers for standard interrupt handling
    scribd.com+9s-o-c.org+9en.wikipedia.org+9
    .

    Abort (ABT) – Handles memory-related exceptions such as prefetch or data faults
    twiserandom.com+15s-o-c.org+15fr.scribd.com+15
    .

    Undefined (UND) – Triggered when the CPU encounters an undefined instruction
    reddit.com+15s-o-c.org+15fr.scribd.com+15
    .

    Monitor (MON) – Used for TrustZone security, switching between secure and non-secure states (ARMv6+ with security extensions)
    twiserandom.com+3onlinedocs.microchip.com+3en.wikipedia.org+3
    .

    Hypervisor (HYP) – For virtualization (ARMv7+), managing guest OS contexts at higher privilege .

 
cavil board using which arm cortex based?
no
In CISC and RISC Which executes faster and why?

Overall, RISC processors tend to execute faster per instruction because they use simple, single-cycle operations and optimized pipelining.

CISC processors, like x86, pack more features per instruction and may use fewer instructions overall, but have slower instruction execution due to complex decoding. 


