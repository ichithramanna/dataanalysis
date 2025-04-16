# AUTOSAR CAN Frame Test Generator

This project provides a Python script that parses AUTOSAR-compliant XML files describing CAN-FRAME and signal configurations. It extracts information to automatically generate test documentation and code files useful for embedded software validation and CAN signal analysis.

## 📁 Features

- Parses AUTOSAR XML files to extract:
  - CAN frame identifiers and directions
  - I-Signals and their properties
  - Signal groups, lengths, and timeout information
  - Transmission modes and periodicity
- Generates:
  - Excel reports (SRS and ITP formats)
  - C header files (`*.h`) and source code (`*.c`) for automated test application
  - CAPL scripts (`*.c`) for CANalyzer signal validation

## 🛠 Requirements

- Python 3.x
- Dependencies:
  - `pandas`
  - `xlwt`
  - `openpyxl`
  - `tkinter` (for file dialog GUI)

Install dependencies using pip:

```bash
pip install pandas xlwt openpyxl
