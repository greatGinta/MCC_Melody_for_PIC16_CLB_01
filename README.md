# MCC Melody for PIC16 - CLB AND Gate

Implement a hardware AND gate using the Configurable Logic Block (CLB) 
on PIC16, configured via MCC Melody — no firmware logic required.

## 📹 Video Tutorial
https://youtu.be/nGulfH0APz4

## 🛠️ Tools & Hardware
- MPLAB X IDE v6.25
- MCC Melody
- PIC16F13145 Curiosity Nano (EV06M52A)
- Curiosity Nano Explorer (EV58G97A)

## 📋 What it does
- Configures CLB1 as a hardware AND gate
- LED0 on Curiosity Nano lights up only when both switches are pressed simultaneously
- Logic runs entirely in hardware via CLB — no code needed in main.c
