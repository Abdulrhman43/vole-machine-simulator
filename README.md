# 🖥️ Vole Machine Simulator 🚀

---

## 📌 Overview  
This project is a **simulator** for the Vole machine and its assembly-like language.  
It allows users to:
- Load programs from files
- Execute instructions **step-by-step**
- Display the system status (Registers, Memory, PC, IR, and Screen)

The simulator is designed using **Object-Oriented Programming (OOP)** principles to ensure **modularity** and **scalability**.

---

## ✅ Features
- ✅ Load and run Vole machine programs
- ✅ Step-by-step instruction execution
- ✅ Validate and execute instructions
- ✅ Display system state in a structured text format
- ✅ Ignore invalid instructions gracefully

---

## 🧾 Supported Instructions  
The simulator supports the following Vole machine instructions:

- `LOAD`  – Load register from memory or immediate value  
- `STORE` – Store register value in memory or screen  
- `MOVE`  – Copy values between registers  
- `ADD`   – Integer and floating-point addition  
- `JUMP`  – Conditional jumps  
- `HALT`  – Stop execution

---

## ⚙️ How It Works

1️⃣ **Load a program** from a file (space-separated instructions)  
2️⃣ The simulator **fetches and executes** instructions step by step  
3️⃣ At each step, it updates:
- Registers
- Memory
- Program Counter (PC)
4️⃣ Users can view the **system status** after each step or at the end of execution

---

## 🛠️ Technologies Used

- `C++` – for implementation  
- `Object-Oriented Programming (OOP)` – for modular design  
- `File Handling` – for loading programs from external files  
- `Memory Management` – to simulate registers and execution flow  

---

> Feel free to explore, run, or modify the simulator as needed.  
> Contributions and suggestions are always welcome!
