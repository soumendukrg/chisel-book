# DTU 02139: Digital Electronics 2

This course is a follow up of Digital Electronics 1 for students of Electrical Engineering at DTU, but can also be taken from other study lines.

*This course is being restructured and therefore this web page is under constant change.*

### Aims of the course

### Tentative List of Topics

### Prerequisites

The course is intended for students enrolled in the bachelor program in electrical engineering or bachelor students from software engineering with an interest in
hardware design. Knowledge on following topics is a prerequisite:

 * Boolean algebra
 * Basic digital structures (e.g., AND gate, register)
 * Computer usage as a developer (text/program editor, file system, command line interface)
 * Basic programming

Depending on your background the prerequisites are covered in one of following courses:

 * 02138 Digital Electronics 1
 * 02132 Computer Systems
 * 02135 Introduction to Cyber Systems

### Schedule, Format, Place

The course is lectured Thursday afternoons 13:00 - 17:00.
The course is lectured in English.

First part is usually lectures and second part for project work.
Students will work in groups of two or three on small lab exercises
and as a final project on a vending machine.

The course is lectured in building 341, room 22. The lab is in building
308, rooms 117 and 127.

### Pensum List

TBD 

## Recommended Textbook

 * Dally: [Digital Design Using VHDL a Systems Approach](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=3&cad=rja&uact=8&ved=2ahUKEwiijsD_76vmAhW4AxAIHci4Ai8QFjACegQIAhAB&url=https%3A%2F%2Fwww.cambridge.org%2Fcore%2Fbooks%2Fdigital-design-using-vhdl%2F0649D96BCF9E14D1AC4D192D629A3E5A&usg=AOvVaw3f4XcAOJdrcFfY6QdnGvRm)
 * Schoeberl: [Digital Design with Chisel](http://www.imm.dtu.dk/%7Emasca/chisel-book.html)

The Dally book is available from
[Polyteknisk Boghandel](http://www.polyteknisk.dk/)
in Building 101A.

## Resources

 * [Lab Material](https://github.com/schoeberl/chisel-lab)
 * [The Chisel Book](http://www.imm.dtu.dk/%7Emasca/chisel-book.html)
 * [Chisel](https://www.chisel-lang.org/)
 * [Anonymous Feedback Inbox](https://docs.google.com/forms/d/e/1FAIpQLSclKyEM_foF7U0TF-CoIZhla5EFEcE8-EGD7Jvle6TBB90WZw/viewform?vc=0&c=0&w=1&usp=mail_form_link)

## Instructor

[Martin Schoeberl](http://www.imm.dtu.dk/%7Emasca/)

## Lecture Plan (2020)

### Week 1 Introduction

**Topics:** Introduction and motivation, languages for hardware design, testing (see 2.1.4), tools and setup, a first round in Chisel

**Lab:** Chisel “Hello World”

**Reading:** Chisel: 1, 2, Dally: 2.1.4 

**Optional reading:** Dally: 1, 2


### Week 2 Basic Digital Circuits in Chisel

**Topics:** Recap combinational and synchronous circuits with Chisel code (including comparison with VHDL)

**Reading:** Dally 8, 14.1., 14.2 and Chisel 5

**Lab:** Basic circuits in Chisel, given testers, diagram to code and code to diagram exercises. TODO: look into Dally 7 examples for the lab. One example with the FPGA board.


### Week 3 Timing

**Topics:** Delay and Power, Timing, and Metastability

**Reading:** Dally: 5.1-5.4, 15.1-15.6, and 28.1-28.4

**Lab:** 15.1, 15.10, 15.11, 15.12, 15.19, 15.20, 15.21


### Week 4 Small Sequential Circuits, Components

**Topics:** Composing circuits out of components, sequential building blocks

**Reading:** Dally: x Chisel: 5 and 6

**Lab:** Sequential circuits and components, maybe blinking LED or PWM with counters


### Week 5 Testing and Verification

**Topics:** Testing and verification in Chisel, using CLI, unit tests, waveform viewing

**Reading:** Dally: 20, Chisel: 3, maybe some text on test driven development

**Lab:** Hexadecimal to 7 segment decoder, Chisel unit testers and debugging with gtkwave, (tester for 7 segment decoder)


### Week 6 State Machines

**Topics:** Some more Chisel, state machine (repetition)

**Reading:** Dally: 14.3-14.5, Chisel: 8 (2nd edition)

**Lab:**  7 segment display with a counter


### Week 7 State Machine and Datapath, Input interface

**Topics:** State machine and datapath (FSMD)

**Reading:** Dally: 16, Chisel: 9.2 (2nd edition), 7

**Lab:** Dally 14.28 and other, FSM exercises in Chisel


### Week 8 State Machines and Refactoring (1 hour)

**Topics:** State Machines and Refactoring

**Reading:** Dally: 17

**Lab:** Full display


### Week 9 Communications State Machines (1 hour)

**Topics:** Communicating FSMs and ready/valid interface

**Reading:** Dally: 22, Chisel: 9.1

**Lab:** Full display


### Easter Week


### Week 10 No lecture

**Lab:** work on vending machine


### Week 11 No lecture

**Lab:** work on vending machine


### Week 12 Microcoded State Machine, Pipelining, Memory

**Topics:** Microcoded FSMs, pipelining, and interconnect

**Reading:** Dally 18, 23.1-23.4, 24 Chisel 6.x

**Lab:** 18.1 and 18.2, 23.1-23.4, 24.1, (24.2), maybe SRAM exercise


### Week 13 Outro, A Simple Processor

**Topics:** Leros as a simple processor, Discussion of course, and followup courses

**Lab:** Exam examples from last years, finish vending machine and report
