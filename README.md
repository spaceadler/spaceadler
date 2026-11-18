<div align="center">

# spaceadler

Computer engineering student, working toward flight software and FPGA design.

![Focus](https://img.shields.io/badge/Focus-Embedded%20Systems-blue)
![Focus](https://img.shields.io/badge/Focus-Digital%20Logic-purple)
![Interest](https://img.shields.io/badge/Interest-Aerospace-lightgrey)

</div>

---

## About

I like knowing what a program does on the hardware it runs on. So far that has meant building a 16-bit computer up from NAND gates in nand2tetris, writing a Tetris game in C that follows MISRA C:2012 and the JPL Power of 10 rules (yes, I know), and measuring how much faster one CPU instruction counts leading zeros than a loop does. Those rules were written for flight software, so technically the Tetris could run on a space station. I also work on Quanser drones in a research lab.

I want to work in aerospace, on systems where the chip and the firmware are designed together rather than one after the other. EAGLE, the rocket flight controller I'm designing, is where I'm working that out: an FPGA votes between three IMUs before the flight computer sees the data. After that I want to get into real-time operating systems.

At home, a Raspberry Pi runs my own cloud: music, films and series, photos, an office suite, my notes, and the Gitea that hosts every repo here, with no cloud provider involved. On top of it runs adlerOS, a macOS-style home screen in the browser that turns every app into a window, with modes for a phone, a TV and a car.

[spaceadler.com](https://spaceadler.com/en/)

---

## Projects

| Project | What it is |
|---|---|
| [EAGLE](https://github.com/spaceadler/EAGLE) | Design study for a rocket flight controller: an MCU running FreeRTOS and F´, and an FPGA that votes between three IMUs (TMR). Docs only so far |
| [spacetetris](https://github.com/spaceadler/spacetetris) | Tetris in C, written to follow MISRA C:2012 and the JPL Power of 10 rules, with the I/O split out so it can be ported to an RTOS |
| [nand2tetris](https://github.com/spaceadler/nand2tetris) | 29 chips in HDL, from a NAND gate to the ALU, RAM, CPU and a complete computer |
| [UART_TX](https://github.com/spaceadler/UART_TX) | UART transmitter in VHDL: 50 MHz clock in, 115,200 baud 8N1 out |
| [NLZ3000](https://git.spaceadler.com/spaceadler/nlz3000) | Counting leading zeros bit by bit vs with one CPU instruction, measured on Arm and x86: 48× and 20× faster |
| [adlerOS](https://github.com/spaceadler/adleros) | Home screen and app store for a self-hosted Docker server |

---

## Tools

**Use regularly**

![VHDL](https://img.shields.io/badge/VHDL-purple?style=flat-square)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![GNU/Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-000000?style=flat-square&logo=tailscale&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Quartus](https://img.shields.io/badge/Quartus-0071C5?style=flat-square)
![GHDL](https://img.shields.io/badge/GHDL-purple?style=flat-square)

**Learning**

![FreeRTOS](https://img.shields.io/badge/FreeRTOS-lightgrey?style=flat-square)
![F´](https://img.shields.io/badge/F%C2%B4-lightgrey?style=flat-square)
![RISC-V](https://img.shields.io/badge/RISC--V-283272?style=flat-square&logo=riscv&logoColor=white)
![Vivado](https://img.shields.io/badge/Vivado-A50034?style=flat-square)

---

## GitHub Stats

<div align="center">

![Languages](github-metrics.svg)

</div>

---

## Working On

- Planning EAGLE's sensor voting on the FPGA and its link to the MCU
- Porting spacetetris to an RTOS
- RISC-V (RV32I) at university

---

<div align="center">

*powered by logic, coffee, and many sleepless nights*

</div>
