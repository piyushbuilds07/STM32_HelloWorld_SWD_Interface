
---

### Project 2: `STM32-SWV-HelloWorld/README.md`

```markdown
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

## How to Access and Run the Project
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/YourUsername/STM32-SWV-HelloWorld.git
