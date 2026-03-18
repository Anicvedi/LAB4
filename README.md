# FPGA Lab Assignment – Radix-4 Booth Multiplier & Debounce Counter

## Course
E3: Digital Systems Design with FPGAs  
IISc Bangalore  

---

## Objective
- Implement pipelined Radix-4 Booth multiplier  
- Handle asynchronous inputs using synchronizer and debounce  

---

## Q1: Radix-4 Booth Multiplier
- 8-bit signed multiplication  
- Pipelined vs Non-pipelined comparison  
- Metrics:
  - LUTs
  - Flip-flops
  - Delay
  - Throughput  

---

## Q2: Debounce Counter
- Push-button input (asynchronous)
- 2-FF synchronizer
- Counter-based debounce (~20ms)
- Up/Down counter

---

## Tools Used
- Vivado
- Verilog HDL

---

## Target FPGA
Xilinx Artix-7 (XC7A35T)