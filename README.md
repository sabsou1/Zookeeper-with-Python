# 🦁 Zookeeper with Python

A Python command-line application built to simulate a zoo monitoring system for habitat cameras.

## 📌 Features & Logic
* **ASCII Art Representations**: Stores multiline raw strings (`r"""..."""`) for 6 different animals (`camel`, `lion`, `deer`, `goose`, `bat`, `rabbit`).
* **Interactive Control Loop**: Uses a continuous `while True` loop to prompt users for habitat numbers without quitting after each selection.
* **List Indexing**: Maps user choices directly to elements inside an `animals` list to render camera feeds dynamically.
* **Graceful Exit**: Ends the interactive loop and prints `"See you later!"` when the user inputs `"exit"`.

## 🛠️ Concepts Applied
* Python 3
* Infinite Loops (`while True` / `break`)
* Data Structures (`lists`, `multiline raw strings`)
* User Input & Type Conversion (`input()`, `int()`)
