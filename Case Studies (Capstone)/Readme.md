# 📘 Capstone Assignment – Computer Organization & Architecture

## 📌 Overview
This repository contains solutions to selected case studies from the **Computer Organization & Architecture (COA)** capstone assignment. The objective is to apply core COA concepts such as processor design, instruction set architecture, pipelining, and I/O systems to real-world scenarios.

### 📂 Case Studies Covered
- 🚦 Case Study 1: Processor Selection for Smart Traffic Control System  
- 🏥 Case Study 2: I/O Design for Hospital Patient Monitoring Unit  

---

# 🚦 Case Study 1: Processor Selection for Smart Traffic Control System

## 🧠 Problem Summary
A smart traffic control system must process real-time data from multiple sensors and dynamically adjust traffic signals. The system requires:
- Low latency response  
- Continuous operation  
- Efficient power consumption  
- High reliability  

---

## ⚙️ COA Concepts Applied
- Functional Units (ALU, CU, Registers, Memory)  
- Instruction Set Architecture (RISC vs CISC)  
- Instruction Throughput (IPC)  
- Instruction-Level Parallelism  
- Pipelining and Pipeline Hazards  

---

## 🔍 Key Analysis
- **RISC architecture** is preferred due to faster execution, simplicity, and better pipeline compatibility.  
- **Pipelining** improves performance by overlapping instruction execution.  
- Pipeline hazards (data, control, structural) are minimized using techniques like forwarding and branch prediction.  

---

## 🏗️ Design Decision
A **pipelined RISC processor** is recommended to:
- Improve instruction throughput  
- Reduce latency  
- Enhance CPU utilization  

---
## ✅ Conclusion
A pipelined RISC architecture provides the required speed, efficiency, and reliability for real-time traffic management systems.

---

# 🏥 Case Study 5: I/O Design for Hospital Patient Monitoring Unit

## 🧠 Problem Summary
A hospital monitoring system continuously tracks patient vitals and must generate real-time alerts. The system demands:
- Continuous data processing  
- Low latency  
- High reliability  
- Efficient CPU utilization  

---

## ⚙️ COA Concepts Applied
- Memory-Mapped I/O vs I/O-Mapped I/O  
- I/O Techniques (Programmed, Interrupt-Driven, DMA)  
- Data Transfer Mechanisms  
- Buffering  

---

## 🔍 Key Analysis
- **Memory-Mapped I/O** is preferred due to faster access and flexibility.  
- Among I/O techniques:
  - Programmed I/O → inefficient (high CPU usage)  
  - Interrupt-driven I/O → better but causes overhead  
  - **DMA → most efficient (low CPU involvement)**  

---

## 🏗️ Design Decision
A system using **DMA with Memory-Mapped I/O** is recommended to:
- Reduce CPU workload  
- Enable continuous data transfer  
- Improve real-time responsiveness  

---

## ✅ Conclusion
DMA combined with memory-mapped I/O ensures fast, reliable, and efficient real-time patient monitoring.

---


# 👨‍💻 Author
**Mandeep Singh**  
B.Tech CSE (Data Science)  
KR Mangalam University
