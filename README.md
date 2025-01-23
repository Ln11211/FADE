# **FPGA Accelerated Deep-learning Engine**
This project is an implementation of a FPGA accelrated Deep learning engine to run Deep learning models.

The FPGA board chosen for this project is the TUL PYNQ-Z2 Development Board,

![image](https://github.com/user-attachments/assets/7c228562-5d7b-4da6-a86f-0886d5cac1bd)

The Board features the ZYNQ XC7Z020-1CLG400C SOC with

  • 650MHz dual-core Cortex-A9 processor

  • DDR3 memory controller with 8 DMA channels and 4 High Performance AXI3 Slave ports

  • 13,300 logic slices, each with four 6-input LUTs and 8 flip-flops

  • 630 KB of fast block RAM

  • 220 DSP slices

  • 512MB DDR3 memory

### Project Checklist

- [x] Acquire AMD DPU 3.0 ip 
- [x] Acquire Tul PYNQ Z2 board files
- [x] DPU ip block design implementation
- [x] DPU synthesis and Bitstream generation
- [ ] DPU sd card image using Petalinux
- [ ] DL classifier training and quantization
- [ ] DNNDK Optimization of DL model
- [ ] Deployment on PYNQ-Z2

# Deep learning processing unit (DPU) ip block design
![image](https://github.com/user-attachments/assets/349b330e-1af6-40fe-9095-83f65f1ceee0)

# DPU Schematic
![image](https://github.com/user-attachments/assets/274e7a00-14d9-4ae5-a13f-54ece829e0db)

# DPU synthesis on Device
![image](https://github.com/user-attachments/assets/bd9a7cdc-8f1e-499f-9552-d4893f72abba)
 
# Tools used
Xilinx Vivado 2020.1
