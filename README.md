# Sensor-Reading-and-Data-Processing-via-SPI-Protocol-with-STM32
SPI üzerinden sıcaklık ya da voltaj verisi okuma → filtreleme (örneğin moving average) → UART üzerinden PC'ye gönderme.
# STM32 SPI Sensor Reading and Processing

This project demonstrates reading sensor data via SPI protocol using STM32F103 and processing the data with a simple moving average filter, then sending the result via UART.

## Features

- SPI communication (HAL)
- 10-point moving average filter
- UART output for debugging or data collection

## Hardware

- STM32F103 (Blue Pill)
- MCP3008 or similar SPI sensor/ADC
- USB to Serial for UART viewing (e.g., Tera Term)

## How to Use

1. Open project in STM32CubeIDE
2. Configure SPI1 and USART1 in CubeMX
3. Flash the code
4. Monitor UART at 9600 baud

## Output Format

