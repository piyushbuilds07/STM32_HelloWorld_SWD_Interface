# STM32 Bare-Metal SWV ITM "Hello World" (NUCLEO-L452RE)

A pure, register-level implementation of `printf` using the ARM Cortex-M4 ITM (Instrumentation Trace Macrocell) and the Single Wire Output (SWO) pin. 

This project was built using an **Empty** STM32CubeIDE project. It bypasses physical UARTs and HAL drivers entirely, demonstrating how to redirect standard C library `printf` output directly to the **SWV ITM Data Console** in STM32CubeIDE using raw ARM Cortex-M and STM32L4 memory-mapped registers.

## Hardware Requirements
*   **Board:** STM32 NUCLEO-L452RE (STM32L452RET6U ARM Cortex-M4)
*   **Connection:** USB Type-A to Mini-B cable (Data-capable)

## Hardware Pinout
| Peripheral | STM32 Pin | Description |
| :--- | :--- | :--- |
| SWO (Trace) | **PB3** | Serial Wire Output for ITM trace data |

<img width="160" height="120" alt="WhatsApp Image 2026-10-03 at 11 26 04 AM" src="https://github.com/user-attachments/assets/4523a3b8-357b-40be-8308-c5cf9639ec39" />

