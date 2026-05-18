# BlueChat — Bluetooth Messenger

## Overview

BlueChat is a Bluetooth messaging application developed using HTML, CSS, and JavaScript. It allows nearby devices to connect through Bluetooth and exchange messages and files in real time. The interface is designed similar to modern messaging applications like WhatsApp.

## Features

* Device discovery using Bluetooth
* Real-time text messaging
* File transfer support
* File transfer progress indicator
* Connection status display
* Automatic reconnection handling
* Message timestamps
* Delivery receipts

## Technologies Used

* HTML5
* CSS3
* JavaScript
* Web Bluetooth API

## Project Structure

BlueChat/
├── index.html
├── README.md

## How to Run

1. Open the project folder.
2. Run index.html using Live Server.
3. Enable Bluetooth on both devices.
4. Click “Scan for Devices”.
5. Connect to a nearby device.
6. Start messaging and file sharing.

## User Interface

The application contains:

* Devices screen for scanning nearby devices
* Chat screen for sending and receiving messages
* File attachment button
* File transfer progress bar

## Bluetooth Service UUIDs

* SERVICE_UUID
* TX_CHAR_UUID
* RX_CHAR_UUID

## File Transfer

Files are transferred in chunks over Bluetooth with live progress updates.

## Browser Support

* Google Chrome ✅
* Microsoft Edge ✅
* Firefox ❌
* Safari ❌

## Future Improvements

* Group chats
* Voice messages
* Better encryption
* Chat history storage

## Author Information

Student: BSCS-6B
Department: Computer Science Department
Institute: Shaheed Zulfikar Ali Bhutto Institute of Science and Technology
Course: Computer Network and Data Communication (CNDC)
