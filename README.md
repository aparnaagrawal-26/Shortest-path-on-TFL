# 🚇 Dijkstra's Algorithm for TfL Rail Network Routing

A Python-based project that models a simplified version of Transport for London's (TfL) rail system. It applies **Dijkstra’s algorithm** to determine the shortest route between two stations, aiming to optimize travel time in urban networks.

---

## 🧭 What This Project Does

1. **Efficient Route Finder:**
   - Implements Dijkstra’s algorithm to compute the fastest path from a source to a destination.
   - Uses a priority-based approach to iteratively select the next optimal station.

2. **Graph-Based Railway Model:**
   - The network is abstracted as a **graph**, where each station is a node and edges carry weights (representing travel times).
   - Input your start and end stations to receive a step-by-step path and total journey duration.

3. **Smart Testing:**
   - The solution includes test cases that handle common and edge travel scenarios.
   - Validates results by reversing routes, comparing outputs, and addressing unlisted stations.

4. **Improvement Scope:**
   - Adaptability for **undirected graphs** to mirror real-world connectivity more closely.
   - Future-proofing via **enhanced input handling** and **real-time data integration**.
   - Planned extensions for **multiple shortest paths**, not just one.

---

## 🔍 Key Features

- 🐍 **Clean Python Implementation**: Modular and readable logic for graph traversal and shortest path calculation.
- 🧪 **Test Scenarios Included**: From basic station hops to more complex routing conditions.
- 📑 **Commented Code**: Designed for both educational and practical reference.

---

## ▶️ How to Run It

1. **Install Python 3.x** if not already installed.
2. **Clone this repo** or download the `Group23.py` file.
3. Customize your station network dictionary (predefined in the code or externally).
4. Call the Dijkstra function with a start and end station.
5. **Output**: A printable route and total journey time are displayed in the terminal.

---

## 🔄 Future Enhancements

- 🔁 Support for **bi-directional routing** (undirected edges).
- 🧠 Integration with **live travel APIs** for real-time disruptions or delays.
- ✅ **Robust validation**: Friendly messages for unlisted or misspelled station names.
- 🌐 GUI or Web dashboard for user interaction.

---

## 📁 Files Included

- `Group23.py`: The main Python script with the algorithm and tests.
- `README.md`: This file.

---

## 👩‍💻 Created By

Aparna A. and team | MSc Business Analytics  

---

> *This project was developed as part of an academic exploration of graph theory and transportation modelling. Feedback and contributions are welcome!*
