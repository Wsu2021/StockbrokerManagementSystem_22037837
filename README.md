# **Stockbroker Management System**

**Student ID:** 22037837  
**Date:** October 2025  
**Language:** Java (JDK 17+)  
**IDE:** Eclipse IDE  

---

## **1. Overview**
A console-based Java program for managing shareholders, portfolios, shares, and trades.  
Implements file-based data storage, modular classes, input validation, and follows the **Google Java Style Guide**.  
No GUI or Java Maps are used.

---

## **2. Main Features**
- Manage shareholders, shares, portfolios, and trade records  
- Perform buy/sell operations  
- Validate user inputs  
- Save and load data from `.txt` files  
- Display summaries via console menu  

---


---

## 🧠 Project Overview

This project simulates a **stockbroker record management system** for *Dee Zaster*, a Sydney-based broker.  
It provides a **menu-driven console interface** that allows users to:

- Load shareholder, portfolio, and share data from text files  
- Update share prices and customer contact details  
- Execute buy/sell share trades with validation  
- Generate detailed portfolio reports  
- Save updated records back to text files  

The system uses **object-oriented design**, following the **Google Java Style Guide**, and is modularized into clear, maintainable classes.

---

## ⚙️ Core Features

- **File Management:** Load and save data from structured text files  
- **Data Validation:** Ensures correct input formats (e.g., phone numbers, share codes)  
- **Trading System:** Simulate buying and selling shares with transaction summaries  
- **Portfolio Reporting:** Generate formatted financial reports for one or all shareholders  
- **Error Handling:** Prevent crashes due to invalid user input  
- **Testing:** Supports functional and boundary case testing as outlined in project requirements  

---

## 📚 Class Overview

| Class | Description |
|-------|--------------|
| `Driver_22037837.java` | Main entry point. Launches the system and displays the main menu. |
| `SystemManager_22037837.java` | Coordinates user interaction, file I/O, and main logic. |
| `Shareholder_22037837.java` | Represents an individual shareholder with contact details and portfolio link. |
| `Portfolio_22037837.java` | Stores multiple shares owned by a shareholder and manages transactions. |
| `Share_22037837.java` | Represents tradable shares with company name, code, and price. |
| `Trade_22037837.java` | Handles buy/sell transactions and trade summaries. |
| `FileManager_22037837.java` | Reads and writes data between text files and memory. |
| `InputValidator_22037837.java` | Provides reusable input validation methods. |

---

## 🧩 Data Files

| File | Purpose | Example |
|------|----------|---------|
| `shareholders_22037837.txt` | Stores shareholder details | `1001,John Smith,45 George St,0412345678,P1001` |
| `portfolios_22037837.txt` | Records shares held in each portfolio | `P1001,BHP,12000,SUN,100` |
| `shares_22037837.txt` | Lists tradable shares and prices | `BHP,BHP Billiton,10.50` |
| `trades_22037837.txt` | Logs trade transactions | `T0001,P1001,BHP,Buy,100,10.50,2025-10-08,1050.00` |

---

## 🚀 How to Run in Eclipse

1. **Open Eclipse** and create a new **Java Project** → name it `StockbrokerProject`.
2. Inside the `src` folder, add all `.java` files listed above.
3. Create a new folder named `data` at the root level.
4. Add all `.txt` data files inside the `data` folder.
5. Set `Driver_22037837.java` as the main class.
6. Click **Run ▶** to start the program.
7. Use the on-screen menu to navigate through program options.

---

## 🧪 Testing

A separate document **`Testing_22037837.docx`** includes:

- Detailed test cases for all major user stories  
- Valid, edge, and invalid input testing  
- Actual vs. expected output results  
- Summary of limitations and AI adaptation notes  

---
