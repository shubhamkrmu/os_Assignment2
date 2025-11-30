OS Lab Assignment 2 — System Startup & Process Simulation

This project simulates a basic operating system startup, process creation, and process termination using Python’s multiprocessing and logging modules.

It demonstrates how an OS:

Initializes system components

Spawns multiple processes

Tracks process execution

Performs a clean shutdown

Features

✔ System startup simulation
✔ Creation of multiple child processes
✔ Logging of process start & end times
✔ Generation of process_log.txt
✔ Proper process synchronization using join()

Technologies Used

Python 3.x

multiprocessing module

logging module

time module

How It Works

Logging is initialized to record timestamps and process names.

A dummy task (system_process) simulates system processes.

Two child processes are created and started concurrently.

Each process logs its start and end.

The system waits for all processes and performs a clean shutdown.

How to Run
python3 assignment2.py


You will see:

System Starting...
System Shutdown.


A log file process_log.txt will be generated with entries such as:

2025-07-16 12:35:21 - Process-1 - Process-1 started
2025-07-16 12:35:23 - Process-1 - Process-1 ended

Files Included
assignment2.py          # Main script
process_log.txt         # Auto-generated log file
README.md               # Documentation
report.pdf (optional)   # Short explanation of implementation
