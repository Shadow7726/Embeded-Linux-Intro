### List of essential keywords and concepts that are useful to understand before starting IoT security testing. This table includes the term, its full form (if applicable), and a brief description.

| **Keyword**          | **Full Form**                         | **Description**                                                                                                               |
|----------------------|---------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|
| **UART**             | Universal Asynchronous Receiver-Transmitter | A serial communication protocol commonly used in IoT devices for debugging and direct hardware access.                       |
| **JTAG**             | Joint Test Action Group              | A hardware interface standard used for debugging and testing; often allows low-level access to the device.                    |
| **SPI**              | Serial Peripheral Interface          | A protocol for high-speed data transfer between microcontrollers and small peripherals such as sensors and flash memory.      |
| **I2C**              | Inter-Integrated Circuit             | A communication protocol for connecting low-speed peripherals to microcontrollers, often used in sensor interfacing.         |
| **SoC**              | System on Chip                       | A single chip that integrates all components of a computer or device, including CPU, memory, and input/output ports.         |
| **PCB**              | Printed Circuit Board                | The physical board that holds electronic components in an IoT device, including traces for signal and power routing.         |
| **OTP**              | One-Time Programmable                | Memory that can be written once; used for storing security keys or sensitive configuration data permanently.                 |
| **TPM**              | Trusted Platform Module              | A dedicated security chip that stores cryptographic keys securely; often used in IoT for secure boot and encryption.         |
| **OTA**              | Over-the-Air                         | A method for remotely updating firmware or software on a device without requiring physical access.                           |
| **MCU**              | Microcontroller Unit                 | A compact processor used in embedded systems, containing CPU, memory, and I/O interfaces.                                    |
| **Bootloader**       | -                                    | A program that initializes the hardware and loads the operating system on startup.                                           |
| **Secure Boot**      | -                                    | A security feature that ensures only trusted firmware and OS components are loaded at boot time.                             |
| **Firmware**         | -                                    | Low-level software that controls hardware directly and is usually stored in non-volatile memory.                             |
| **EEPROM**           | Electrically Erasable Programmable Read-Only Memory | Non-volatile memory used to store small amounts of data that must be preserved between reboots. |
| **RAM**              | Random Access Memory                 | Volatile memory used for temporary data storage while a device is powered on.                                                |
| **Flash Memory**     | -                                    | Non-volatile storage used for firmware and configuration data in IoT devices.                                                |
| **SSH**              | Secure Shell                         | A protocol for secure remote access to the command line of a device.                                                         |
| **SSL/TLS**          | Secure Sockets Layer / Transport Layer Security | Cryptographic protocols used to secure communication channels between devices and servers.               |
| **MQTT**             | Message Queuing Telemetry Transport  | A lightweight messaging protocol for IoT devices, commonly used for communication over low-bandwidth networks.               |
| **BLE**              | Bluetooth Low Energy                 | A wireless protocol optimized for low power and short-range communication between IoT devices.                               |
| **GPIO**             | General-Purpose Input/Output         | Pins on a microcontroller or SoC used for interfacing with other hardware components, sensors, or actuators.                |
| **ADC**              | Analog-to-Digital Converter          | A component that converts analog signals (e.g., from sensors) into digital data for processing by the device.                |
| **DAC**              | Digital-to-Analog Converter          | Converts digital signals to analog output, useful for devices that need to send analog signals.                              |
| **PWM**              | Pulse Width Modulation               | A technique used to control the power supplied to devices, often used in motor control and LED dimming.                     |
| **Binwalk**          | -                                    | A tool for analyzing and extracting firmware images, commonly used in IoT firmware analysis.                                |
| **Burp Suite**       | -                                    | A popular tool for web application security testing, useful for IoT devices with web interfaces.                            |
| **Wireshark**        | -                                    | A network protocol analyzer that captures and inspects data packets sent over a network.                                     |
| **Packet Sniffing**  | -                                    | The practice of capturing and analyzing network traffic to detect vulnerabilities or sensitive information leaks.            |
| **Hardcoded Credentials** | -                               | Credentials embedded in firmware or software code, often a vulnerability as it provides attackers with unauthorized access.  |
| **Reverse Engineering** | -                                | The process of analyzing hardware or software to understand its functionality, commonly used in IoT security testing.        |
| **Cryptographic Keys** | -                                 | Keys used in cryptographic functions to secure data; proper key management is critical in IoT security.                     |
| **Attack Surface**   | -                                    | The total set of points where an attacker could attempt to exploit a system.                                                 |
| **Side-Channel Attack** | -                                | An attack that exploits information leakage from a device, such as power consumption or electromagnetic emissions.          |
| **Privileged Access** | -                                  | Elevated access rights (e.g., root or admin) that grant full control over the device.                                        |
| **Fuzzing**          | -                                    | A testing technique that sends random or malformed data to a program to discover vulnerabilities.                           |
| **CAN Bus**          | Controller Area Network              | A robust communication protocol used in automotive and industrial applications, often targeted in IoT hardware hacking.     |
| **GPIO Lockdown**    | -                                    | Security measure to restrict access to GPIO pins to prevent unauthorized hardware manipulation.                              |
| **UART Lockdown**    | -                                    | A method to restrict access to the UART port to prevent unauthorized debugging or direct control of the device.              |
| **HAB**              | High Assurance Boot                  | A secure boot feature in some processors that ensures only trusted firmware is executed.                                    |

These keywords cover a range of IoT security basics and will help build a foundation for IoT hardware and firmware testing.
