# Priority Appointment Scheduler (BST)

A C++ console application that manages patient appointments using a Binary Search Tree (BST), ordered by priority level, so urgent cases can be found and displayed quickly.

## Overview

Appointments are stored in a BST keyed on priority level. This allows efficient scheduling, searching, cancellation, and range-based queries (e.g. "show all appointments more urgent than X") using standard BST traversal and deletion logic.

## Features

- **Schedule** a new appointment (name, priority level, department)
- **Display all** appointments in priority order (in-order traversal)
- **Search** for appointments by priority level
- **Cancel** all appointments matching a given priority level
- **Display more urgent than** a given priority level
- **Display less urgent than** a given priority level

## How it works

Appointments load from `input.txt` on startup (format: count, then name / priority / department per entry), after which the program presents an interactive menu for further scheduling, searching, and cancelling.

## Files

- `main.cpp` — Entry point, menu loop, file input handling
- `BST.h` — `appointment`, `Node`, and `BST` class implementation
- `input.txt` — Initial appointment data loaded at startup

## How to Run

```bash
g++ main.cpp -o scheduler
./scheduler
```

Make sure `input.txt` is in the same directory when running.

## Author

Jana Mohamed Tamer — 20245015
Menna Allah Mostafa — 20245067
