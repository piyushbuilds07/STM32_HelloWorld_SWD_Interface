# STM32 Bare-Metal LED Blink (NUCLEO-L452RE)

A pure, register-level C application written from scratch to blink the on-board user LED (LD2) on the STM32 NUCLEO-L452RE development board. 

This project was built using an **Empty** STM32CubeIDE project. It uses **zero** HAL drivers, zero LL drivers, and zero auto-generated code. Every hardware interaction is done by writing directly to memory-mapped registers.

## Hardware Requirements
*   **Board:** STM32 NUCLEO-L452RE (STM32L452RET6U ARM Cortex-M4)
*   **Connection:** USB Type-A to Mini-B cable (Data-capable)

## Hardware Pinout
| Peripheral | STM32 Pin | Description |
| :--- | :--- | :--- |
| User LED (LD2) | **PA5** | Toggle output to blink the green LED |
