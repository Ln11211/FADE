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

- [x] DPU ip block design implementation
- [x] DPU synthesis and Bitstream generation
- [x] DPU sd card image using Petalinux
- [x] DL classifier training and quantization
- [x] DNNDK Optimization of DL model
- [x] Deployment on PYNQ-Z2

# Deep learning processing unit (DPU) ip block design
![image](https://github.com/user-attachments/assets/349b330e-1af6-40fe-9095-83f65f1ceee0)

# DPU Schematic
![image](https://github.com/user-attachments/assets/274e7a00-14d9-4ae5-a13f-54ece829e0db)

# DPU synthesis on Device
![image](https://github.com/user-attachments/assets/bd9a7cdc-8f1e-499f-9552-d4893f72abba)

# Utilization Report
![image](https://github.com/user-attachments/assets/3daf28a6-26eb-47f2-8efd-06be26151a4e)

# On board deployment
![result1_pov](https://github.com/user-attachments/assets/ac76141b-0735-4794-ad9e-9ea1b652a788)

# 
![result1](https://github.com/user-attachments/assets/327f98cc-9561-4d76-9cbf-4abd32aae0b8)

# Real Time object detection on PYNQ Z2
https://github.com/user-attachments/assets/13b54ebd-84b7-418b-ba39-73301d6a345c


# Behind the project
![hard_work](https://github.com/user-attachments/assets/4a7ed014-ea91-4afd-abae-ff08c3fea5e7)

![hard_work_again](https://github.com/user-attachments/assets/5c1b7497-b0c0-417a-83c6-8e6296bfd5c2)

![Screenshot 2025-02-28 114856](https://github.com/user-attachments/assets/6aa3a7dd-4c1e-4e6d-8072-7f9e5932f760)


# Tools used
Xilinx Vivado 2020.1

DNNDK

MobaXterm
