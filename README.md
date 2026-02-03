# API-Simulator
This project simulates kernel-level process and memory management, interrupts, FORK/EXEC system calls, and trace-driven execution. It was completed as an assignment for the SYSC4001 Operating Systems course at Carleton University.
# Environment / Reqirements
**Operating System:** Linux (Ubuntu recommended)
**Compiler:** g++
**Libraries:** Standard C++ Library (no external dependencies)
**Terminal:** For running the simulation

[!NOTE]
This project was tested in WSL, providing a Linux-compatible environment on Windows. Behavior may differ on different environments.

## Running the Simulator

1. **Compile the code:**
#run the build script :
```
source build.sh
```
3. **Run the simulator with trace and configuration files**
```
./interrupts "program1.txt" "vector_table.txt" "device_table.txt" "external_files.txt"
```
