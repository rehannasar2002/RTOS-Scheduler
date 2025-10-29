# RTOS Scheduler Design in ARM Cortex-M Assembly

### 🛠️ Tools  
**ARM Cortex-M**, **Assembly**, **QEMU**, **GitHub Codespaces**

---

## 🧩 Overview  
This project implements a **basic RTOS scheduler** from scratch using **ARM Cortex-M assembly language**.  
The goal is to understand how task scheduling, context switching, and interrupt handling work at the CPU level without relying on any existing RTOS frameworks.

---

## ⚙️ Features  
- Implements a **round-robin scheduler** for multiple tasks  
- Demonstrates **manual context switching** using stack operations  
- Utilizes **SysTick timer** for periodic task switching  
- Handles **exceptions** and **interrupts** at the assembly level  
- Runs entirely on **QEMU Cortex-M emulator**, no physical hardware required  

---

## 🧠 Learning Outcomes  
- Deep understanding of **RTOS internals** and **CPU context management**  
- Hands-on experience in **ARM Cortex-M assembly programming**  
- Knowledge of **exception entry/exit mechanisms** and **interrupt-driven scheduling**

---

## 🧪 Setup & Execution  

### Prerequisites  
- GitHub Codespaces or local setup with:  
  - **QEMU for ARM Cortex-M**  
  - **GNU Arm Embedded Toolchain** (`arm-none-eabi-gcc`, `arm-none-eabi-gdb`)

### Steps  
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/rtos-scheduler-assembly.git
   cd rtos-scheduler-assembly
