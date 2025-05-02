# JPN Reconnaissance Tool [Version 1.00]

**JPN Reconnaissance Tool** is a command-line application designed for IT analysts to collect and manage computer system information. This tool allows users to gather and save important details about the computer's hardware and network settings to a CSV file. It also provides options to delete data, remove duplicate entries, and handle system data efficiently.

---

## Features

- **Add Data**: Collects and saves computer details like equipment type (Desktop or Laptop), model, operating system, serial number, KEWPA number, PC name, and IP address to a CSV file.
- **Delete Data**: Allows the user to delete a row from the CSV file based on the serial number.
- **Remove Duplicate Serial Numbers**: Identifies and removes duplicate rows based on the serial number field in the CSV file.
- **Exit**: Exit the program with a countdown timer.
  
---

## Installation

Ensure you have Python 3.x installed.

### Required Python Modules
- `os`
- `platform`
- `csv`
- `subprocess`
- `socket`
- `time`
- `msvcrt` (Only for Windows)

---

## Usage

### Running the Script

1. Clone this repository or download the script.
2. Open a terminal or command prompt.
3. Run the script using Python:

```bash
python jpn_reconnaissance.py
