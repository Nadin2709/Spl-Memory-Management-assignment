# Spl-Memory-Management-assignment
Systems Programming -- Assignment 1 - Coalition-Race

This repository contains my solution for Assignment 1 in the Systems Programming course.

C++ -- Object-Oriented Simulation

---

Overview

This project implements a simulation of a political "coalition race" using object-oriented design in C++.

The system models parties and agents that interact over a graph to form coalitions based on different strategies.

According to the assignment :contentReference[oaicite:0]{index=0}, the goal is to design an efficient system with proper memory management and no leaks.

---

Implemented

- Graph-based simulation (parties as nodes, connections as edges)
- Agents that make offers to neighboring parties
- Coalition formation logic with multiple strategies:
  - SelectionPolicy (Mandates / Edge Weight)
  - JoinPolicy (Mandates / Last Offer)
- Simulation flow with iterations and state transitions
- JSON-based input and output handling

---

Features

- Object-Oriented Design (multiple classes and interactions)
- Use of Rule of Five for memory safety
- Dynamic simulation with cloning of agents
- Efficient memory management (no leaks)

---

Build & Run

make  
./bin/cRace <config_file.json>

---

Environment

C++ (C++11)  
Linux / Unix  

---

Notes

- Focus on OOP design and memory management
- Emphasis on clean architecture and efficiency
- Tested with Valgrind to ensure no memory leaks
