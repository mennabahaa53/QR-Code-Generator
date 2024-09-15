# QR-Code-Generator
QR Code Generation and Tracking System
This repository contains a Python-based system for generating and managing QR codes that can only be used once. It includes both the QR code generation script and a Flask-based server to track QR code usage. This setup is ideal for applications where you need to ensure that each QR code can only be scanned once, such as event tickets, secure access codes, or one-time promotional offers.

Features
QR Code Generation: Generate QR codes with unique identifiers for different individuals or items.
One-Time Use: Track and deactivate QR codes after they are scanned to prevent reuse.
Flask Server: A simple server application to handle QR code scan requests and mark them as used.
File-Based Tracking: Uses text files to keep track of which QR codes have been used.
Prerequisites
Python 3.x
Flask (pip install flask)
qrcode (pip install qrcode[pil])
