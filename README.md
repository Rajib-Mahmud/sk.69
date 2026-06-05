# sk.69

A Python-based reconnaissance and information gathering tool designed for bug bounty hunters and security researchers.

## Overview

sk.69 is a lightweight command-line tool that helps with various reconnaissance tasks commonly used during bug bounty hunting and penetration testing. It combines multiple utilities into a single script for faster workflow.

Note: This project is currently in early development and the codebase is being refactored.

## Features

- ASN to IP range extraction
- Live host checking and validation
- IP range generation and manipulation
- Domain and IP conversion utilities
- Exposed environment file (.env) and debug endpoint scanner
- Automated IP and URL generation

## Requirements

- Python 3.8 or higher
- colorama
- requests

## Installation

Clone the repository and install the required dependencies:

git clone https://github.com/Rajib-Mahmud/sk.69.git
cd sk.69
pip install colorama requests

## Usage

Run the tool using the following command:

python Tool.py

After launching, an interactive menu will appear. Select the desired option by entering the corresponding number.

## Available Modules

1. ASN IP Grabber - Extract IP ranges from ASN numbers
2. Live IP Checker - Check live hosts from a list of IPs
3. IP Ranger - Generate and manipulate IP ranges
4. Domain to IP - Resolve domains to IP addresses
5. Env + Debug Scanner - Scan for exposed .env and debug files
6. 0/21 Adder - IP range manipulation utility
7. IP to Domain - Reverse IP to domain lookup
8. IP Generator - Generate random IP addresses
9. URL Generator - Generate URLs from IP or domain lists

## Disclaimer

This tool is intended solely for educational purposes and authorized security testing.

- Only use this tool against targets you have explicit written permission to test.
- Unauthorized access, scanning, or data collection is strictly prohibited and may be illegal.
- The developer assumes no responsibility for any misuse or damage caused by this tool.

Use at your own risk and always follow ethical guidelines.

## License

This project is licensed under the MIT License.
