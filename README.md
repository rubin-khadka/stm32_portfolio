# STM32 Project Portfolio

A collection of my STM32 projects demonstrating various embedded systems concepts.

## 📊 Overview
- **Total Projects:** 25+
- **Microcontrollers:** STM32F103C8 (Blue Pill), STM32F4
- **Development:** HAL, Bare-metal, FreeRTOS, CubeMX

## 📁 Projects by Category

### 🔹 FreeRTOS Projects
| Project | Description | Key Features |
|---------|-------------|--------------|
| [STM32_FreeRTOS_Software_Timer](https://github.com/rubin-khadka/STM32_FreeRTOS_Software_Timer) | Software timer examples | Timers, callbacks |
| [STM32_FreeRTOS_Mutex](https://github.com/rubin-khadka/STM32_FreeRTOS_Mutex) | Mutex synchronization | Resource protection |
| [STM32_FreeRTOS_Structured_Queue](https://github.com/rubin-khadka/STM32_FreeRTOS_Structured_Queue) | Queue with structured data | Task communication |
| [STM32_FreeRTOS_Simple_Queue](https://github.com/rubin-khadka/STM32_FreeRTOS_Simple_Queue) | Basic queue example | UART, ISR |
| [STM32_FreeRTOS_Counting_Semaphore](https://github.com/rubin-khadka/STM32_FreeRTOS_Counting_Semaphore) | Resource pool management | ISR, multi-priority |
| [STM32_FreeRTOS_Binary_Semaphore](https://github.com/rubin-khadka/STM32_FreeRTOS_Binary_Semaphore) | Task synchronization | CMSIS-RTOS |
| [STM32_FreeRTOS_Task_Creation_Operations](https://github.com/rubin-khadka/STM32_FreeRTOS_Task_Creation_Operations) | Task management | Create/suspend/terminate |

### 🔹 IoT & Cloud Projects
| Project | Description | Technologies |
|---------|-------------|--------------|
| [STM32_MicroSD_Cloud_Logger](https://github.com/rubin-khadka/STM32_MicroSD_Cloud_Logger) | SD card + ThingSpeak upload | ESP8266, FatFS, DHT11, MPU6050 |
| [STM32_ESP8266_DHT11_Thingspeak](https://github.com/rubin-khadka/STM32_ESP8266_DHT11_Thingspeak) | DHT11 to ThingSpeak | AT commands, ESP8266 |
| [STM32_ESP8266_IP_ATCommand](https://github.com/rubin-khadka/STM32_ESP8266_IP_ATCommand) | ESP8266 driver | WiFi modem, AT commands |

### 🔹 Multi-Sensor & Datalogger Projects
| Project | Sensors | Features |
|---------|---------|----------|
| [STM32_MultiSensor_MicroSD_Datalogger](https://github.com/rubin-khadka/STM32_MultiSensor_MicroSD_Datalogger) | DHT11, DS18B20, MPU6050 | SD card, LCD, UART |
| [STM32_MultiSensor_FlashStorage](https://github.com/rubin-khadka/STM32_MultiSensor_FlashStorage) | DS18B20, MPU6050 | W25Q64 flash, circular buffer |
| [STM32_DHT11_MPU6050_LCD](https://github.com/rubin-khadka/STM32_DHT11_MPU6050_LCD) | DHT11, MPU6050 | I2C LCD, bare-metal |
| [STM32_RTC_DS3231_LCD](https://github.com/rubin-khadka/STM32_RTC_DS3231_LCD) | DS3231 RTC | I2C, custom drivers |
| [STM32_DHT11_LCD16x2](https://github.com/rubin-khadka/STM32_DHT11_LCD16x2) | DHT11 | HAL, I2C LCD |
| [STM32_rtc_sensor_logger](https://github.com/rubin-khadka/STM32_rtc_sensor_logger) | RTC + sensors | Data logging |

### 🔹 Bare-Metal & Register-Level Projects
| Project | Description |
|---------|-------------|
| [STM32_BareMetal_BlinkLed_Keil](https://github.com/rubin-khadka/STM32_BareMetal_BlinkLed_Keil) | 72MHz clock config, register-level LED control |
| [STM32_BareMetal_BlinkLed_STM32cubeIDE](https://github.com/rubin-khadka/STM32_BareMetal_BlinkLed_STM32cubeIDE) | Pure register-level, no HAL |
| [STM32_DHT11_UART_BareMetal](https://github.com/rubin-khadka/STM32_DHT11_UART_BareMetal) | DHT11 with register access, UART output |
| [STM32_Digital_Thermometer_BareMetal](https://github.com/rubin-khadka/STM32_Digital_Thermometer_BareMetal) | LM35 + 7-segment, register-level |
| [STM32_UART_LCD_Dashboard](https://github.com/rubin-khadka/STM32_UART_LCD_Dashboard) | UART + LCD, DWT timers |

### 🔹 Additional STM32 Projects
| Project | Description |
|---------|-------------|
| [STM32_Digital_Thermometer](https://github.com/rubin-khadka/STM32_Digital_Thermometer) | LM35 + shift registers, CubeMX |
| [STM32_Thermometer_DataLogger](https://github.com/rubin-khadka/STM32_Thermometer_DataLogger) | 3x LM35 sensors, ADC with DMA, SD card |
| [STM32_UART_LCD_Control_Panel](https://github.com/rubin-khadka/STM32_UART_LCD_Control_Panel) | UART command processing |
| [STM32_UART_LCD_Dashboard](https://github.com/rubin-khadka/STM32_UART_LCD_Dashboard) | Register-level UART + LCD |

---

*More projects added regularly.*
