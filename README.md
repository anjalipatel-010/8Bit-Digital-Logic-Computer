# 🖥️ 8-Bit Digital Logic Computer

This repository showcases the design and construction of a fundamental 8-bit computer built using basic digital circuits. It's an excellent resource for learning about digital electronics, computer architecture, and how data is processed and instructions are executed—bit by bit.

---

## 📘 Overview

An 8-bit computer processes data in 8-bit chunks, meaning its Arithmetic Logic Unit (ALU), registers, and data bus all handle 8-bit values. The system operates through the fetch-decode-execute cycle, where:

* **Clock Circuit**: Provides timing signals to synchronize operations.
* **Registers**: Temporarily store and manage data during computation.
* **ALU**: Performs basic arithmetic and logic operations like addition, subtraction, AND, OR, and XOR.
* **Control Unit**: Decodes instructions and coordinates the activities of different components.
* **Memory**: Divided into RAM (stores temporary data) and ROM (holds permanent instructions).
* **Bus System**: Allows communication between components, with the data bus transferring data, the address bus selecting memory locations, and the control bus managing read and write operations.
* **I/O Devices**: Provide interaction with the user.

---

## 🧠 Key Components

### 1. **Registers**

* **Accumulator (A)**: Stores intermediate results.
* **Instruction Register (IR)**: Holds the current instruction.
* **Program Counter (PC)**: Keeps track of the next instruction to execute.

### 2. **Arithmetic Logic Unit (ALU)**

* Performs operations such as addition, subtraction, AND, OR, and XOR on 8-bit values.

### 3. **Control Unit**

* Decodes instructions and generates control signals to coordinate the operation of the computer.

### 4. **Memory**

* **RAM**: Stores temporary data and running programs.
* **ROM**: Holds permanent instructions like a bootloader or microcode.

### 5. **Bus System**

* **Data Bus**: Transfers data between components.
* **Address Bus**: Selects memory locations.
* **Control Bus**: Manages read and write operations.

### 6. **Input/Output Devices**

* Devices like switches, LEDs, and displays that provide interaction with the user.

---

## 🔧 Building the Computer

Constructing this 8-bit computer involves using simple logic chips, such as the 74LS series, along with EEPROM for storing microcode and SRAM for memory. A manual clock can be used for step-by-step debugging, while an oscillator allows continuous program execution.

---

## 📄 Documentation

For a detailed explanation and visual representation of the computer's design, refer to the PDF document:

👉 [8bit\_computer.pdf](https://github.com/anjalipatel-010/8Bit-Digital-Logic-Computer/blob/main/8bit%20computer.pdf)

This document includes:

* **Circuit Diagrams**: Illustrations of the digital circuits used.
* **Component Specifications**: Details about the components involved.
* **Step-by-Step Instructions**: Guidance on assembling the computer.

---

## 📷 Visual Reference

![8-Bit Computer Architecture](https://example.com/8bit_computer_architecture.png)

*Note: Replace the above URL with an actual image URL from your repository or an external source.*

---

## 🛠️ Getting Started

To build this 8-bit computer, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/anjalipatel-010/8Bit-Digital-Logic-Computer.git
   ```

2. **Review the Documentation**:

   * Open the `8bit_computer.pdf` file for detailed instructions and diagrams.

3. **Gather Components**:

   * Refer to the parts list in the PDF to collect all necessary components.

4. **Assemble the Circuit**:

   * Follow the step-by-step instructions to build the computer on a breadboard.

5. **Test the System**:

   * Use the manual clock for step-by-step debugging and ensure all components function correctly.

---

## 📚 Learn More

For additional resources and tutorials on building 8-bit computers, consider exploring the following:

* [Ben Eater's 8-bit Computer Series](https://eater.net/8bit)
* [Teddy Warner's 8-bit Breadboard Computer](https://teddywarner.org/Projects/8-bit/)
* [IEEE NITK's 8-bit Computer Project](https://github.com/IEEE-NITK/8-bit-Computer)

---

Feel free to explore the repository, experiment with the design, and enhance your understanding of digital logic and computer architecture!

---
