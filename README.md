# STM32 Bare-Metal LED Blink (NUCLEO-L452RE)

A bare-metal (register-level) C application designed to blink the on-board user LED (LD2) on the STM32 NUCLEO-L452RE development board. 

This project intentionally avoids using STM32CubeMX generated HAL code, demonstrating how to control STM32L4 peripherals by writing directly to hardware registers.

## Hardware Requirements
*   **Board:** STM32 NUCLEO-L452RE (STM32L452RET6U ARM Cortex-M4)
*   **Connection:** USB Type-A to Mini-B cable (Data-capable)

## Hardware Pinout
| Peripheral | STM32 Pin | Description |
| :--- | :--- | :--- |
| User LED (LD2) | **PA5** | Toggle output to blink the green LED |
