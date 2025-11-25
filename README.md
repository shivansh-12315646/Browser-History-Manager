# Browser History Manager (C++)

## Overview
This project implements a simple browser-history management system using a **stack-based approach** in C++. It simulates how real browsers store visited pages and allow users to navigate backward through history. The program provides a console-based interface where users can visit new URLs, go back to the previous page, and check the current active page.

## Features
- **Visit New Page:** Pushes the entered URL onto the history stack.
- **Go Back:** Pops the current page and moves to the previous one.
- **Current Page View:** Displays the URL at the top of the stack.
- **Stack-Based Implementation:** Mimics how browsers maintain linear navigation history.

## Technologies Used
- **C++**
- **Stack Data Structure**
- **Object-Oriented Programming**
- **Console-Based Application**

## How to Run
1. Compile the program:
   ```bash
   g++ browser_history.cpp -o browser
2. Run:
   ```bash
   ./browser

## Project Structure
- BrowserHistory class manages the stack operations (visitPage(), goBack(), currentPage()).
- main() function provides a menu-driven interface for user interaction.

# Purpose
A small but practical project demonstrating stack operations, class design, and interactive console I/O — ideal for strengthening data-structure knowledge and C++ fundamentals.
