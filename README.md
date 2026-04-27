# 🔷 Implementation of Systolic Array for Matrix Multiplication

## 📌 Overview
This project implements a systolic array architecture in Verilog HDL to perform matrix multiplication efficiently. Unlike conventional sequential methods, this design leverages parallel processing and pipelining to significantly improve computational speed.

## 🚀 Key Highlight
- Achieves approximately **5× faster computation** compared to traditional matrix multiplication methods due to parallel data flow and pipelined processing.

## 🎯 Objectives
- Design a systolic array architecture for matrix multiplication
- Implement the design using Verilog HDL
- Verify functionality using simulation in Xilinx Vivado
- Analyze performance improvement over conventional methods

## 🛠️ Tools & Technologies
- Xilinx Vivado
- Verilog HDL
- Digital Design Concepts

## ⚙️ Working Principle
A systolic array consists of multiple **Processing Elements (PEs)** arranged in a grid. Each PE performs:
- Multiply-Accumulate (MAC) operation
- Data transfer to neighboring elements

### Data Flow:
- Input matrices are fed into the array in a synchronized manner
- Each PE computes partial results and passes data forward
- Final result is obtained after a fixed number of clock cycles

## 🧠 Key Concepts Used
- Systolic Array Architecture
- Parallel Processing
- Pipelining
- Multiply and Accumulate (MAC) Unit
- Clock-driven synchronous design

## 📂 Project Structure
 -> Systolic_array.v
 -> tb_Systolic_array.v
