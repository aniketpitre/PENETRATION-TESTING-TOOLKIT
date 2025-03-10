# Penetration Testing Toolkit

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: ANIKET AMOD PITRE

*INTERN ID*: CT08QWA

*DOMAIN*: CYBER SECURITY & ETHICAL HACKING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH


Description:
**Disclaimer:** This toolkit is for educational purposes only. Use it only on systems you have permission to test.

## Overview

This Python-based toolkit provides a modular framework for penetration testing. It currently includes:
- **Port Scanner:** Scans a target host for open TCP ports.
- **Brute Forcer:** Demonstrates a basic brute-force login attempt.

## Requirements

- Python 3.x

No external libraries are required for the provided modules. (The code uses the standard library.)

## Usage

Run the main script with the module name and appropriate options:

## Port Scanner

python pentest_toolkit.py port_scanner -t example.com --start-port 1 --end-port 1024 -T 100


python pentest_toolkit.py brute_forcer -t http://example.com -u admin -p path/to/password_list.txt --timeout 5

Output:

![Image](https://github.com/user-attachments/assets/c7856fb0-b953-46f5-947c-7c1c44a2984c)


![Image](https://github.com/user-attachments/assets/13a513e0-5cd4-4d1c-a04e-aa1421959f34)

