⚙️ 3-Stage Pipelined ALU Processor – Verilog Implementation
This project implements a 3-stage pipelined ALU processor in Verilog HDL, designed for executing 16-bit Thumb-style instructions. The pipeline enhances instruction throughput and modularity, ideal for FPGA and academic applications.

✅ Key Features
🧱 Pipeline Stages:

IF (Instruction Fetch)

ID (Instruction Decode)

EX-WB (Execute / Write-Back)

🧮 Supported Instructions:

ADD, SUB, AND, OR – basic ALU operations

MUL – via Booth's Algorithm

DIV – via Restoring Division

💾 Instruction Format:

16-bit Thumb-style instruction set

Modular decoding logic and register file design

📊 Pipeline Registers:

IF-ID, ID-EX, EX-WB buffers for inter-stage data/control separation

🔍 Simulation:

Developed and verified in Vivado Design Suite

Waveform analysis for RTL verification

🧠 FPGA Target:

Designed with Spartan-6 compatibility in mind

➡️ To see simulation output, timing summary, and RTL design, please follow the report.