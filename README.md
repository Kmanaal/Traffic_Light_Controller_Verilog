# Traffic_Light_Controller_Verilog

# 🚦 Traffic Light Controller (Verilog FSM)

This project implements a Traffic Light Controller using a Finite State Machine (FSM) in Verilog. The design simulates the behavior of a real-world traffic signal by cycling through three states: Red, Green, and Yellow, each with a defined time duration.

The controller is built using synchronous logic with a clock and reset input. A counter is used to manage timing for each state, and outputs are encoded to represent the active light at any given time.

A testbench is included to verify functionality, generate clock signals, and observe state transitions during simulation.

# 🔧 Features
FSM-based design (Moore model)
Configurable timing using counters
Clean state transitions: Red → Green → Yellow → Red
Fully testable with provided testbench

# 📁 Files
traffic_light_controller.v – Main Verilog module
tb_traffic_light.v – Testbench for simulation

# ▶️ Usage
Run the testbench in any Verilog simulator (ModelSim, Vivado, etc.) to observe the traffic light sequence over time.
