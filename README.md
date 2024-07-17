# Simple Nmap Scanning Tool

This is a simple Nmap scanning tool built with Python that allows you to perform SYN ACK, UDP, and Comprehensive scans on a specified IP address. The results are logged into a file named `scan_results.log`.

## Requirements

- Python 3.x
- `python-nmap` library

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/nmap-scanner.git
    cd nmap-scanner
    ```

2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the script:
    ```bash
    python scanner.py
    ```

2. Follow the prompts to enter the IP address and select the type of scan:
    - SYN ACK Scan
    - UDP Scan
    - Comprehensive Scan

3. The scan results will be printed on the screen and also logged into `scan_results.log`.

## Logging

The scan results are logged in a file named `scan_results.log` with timestamps for better tracking and analysis.
