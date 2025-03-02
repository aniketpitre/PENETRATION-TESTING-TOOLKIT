# Penetration Testing Toolkit

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

### Port Scanner

```bash
python pentest_toolkit.py port_scanner -t example.com --start-port 1 --end-port 1024 -T 100


python pentest_toolkit.py brute_forcer -t http://example.com -u admin -p path/to/password_list.txt --timeout 5
 