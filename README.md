# Console-Based-Food-Shelf-Life-Tracker
Console-Based Food Shelf-Life Tracker – Built in C using structs, file handling, and standard libraries. Tracks food expiry with custom date validation, leap year checks, and a real-time status engine. Persistent storage ensures records are saved, updated, and alerts trigger automatically.
# Console-Based Food Shelf-Life Tracker

## Overview
The Console-Based Food Shelf-Life Tracker is a C-based inventory management system designed to help users monitor food items and their expiration dates. The application allows users to store food item information, track remaining shelf life, and receive alerts for items that are nearing expiration.

This project demonstrates the use of file handling, data structures, and date-based algorithms to create a persistent and efficient inventory tracking system.

## Features
- Add and manage food inventory items
- Track food expiration dates
- Automated expiry alerts
- Persistent storage using file handling
- Date validation with leap year handling
- Real-time shelf life calculation using system time

## Tech Stack
- **Language:** C
- **Concepts Used:** Data Structures (Structs), File Handling
- **Libraries:** stdio.h, time.h

## Project Structure
food-shelf-life-tracker
│
├── main.c
├── inventory.txt
└── README.md
## How It Works
1. The user enters food item details along with expiration dates.
2. The program stores the data using File I/O for persistent storage.
3. The system calculates remaining shelf life using the C Time library.
4. If an item is close to expiration, the program generates an alert.

## Key Learning Outcomes
- Implementing persistent data storage using File I/O
- Designing structured data using C structs
- Building algorithms for date validation and leap year detection
- Using the C Time library for real-time calculations

## Future Improvements
- Add search and filtering functionality
- Improve user interface for better usability
- Add graphical interface using C-based GUI frameworks
