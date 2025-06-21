# ✈️ Flight Planner System

A Python-based flight itinerary planner that models flights as a graph and computes optimal routes using efficient algorithms. This system supports route planning based on three different policies: **least flights**, **cheapest cost**, and a **hybrid of both** under given time constraints.

---

## 🚀 Features

- Models flights and cities using a graph-based representation.
- Implements scheduling policies using BFS and Dijkstra-like strategies:
  - 🛫 **Least Flights Earliest Arrival**
  - 💰 **Cheapest Fare**
  - 🧭 **Least Flights, Then Cheapest Fare**
- Accepts constraints on:
  - Departure time (`t1`)
  - Arrival time (`t2`)
- Custom test cases built-in to validate all three planning strategies.

---

## 🗂️ Project Structure

- flight.py # Flight data model
- planner.py # Core logic for flight planning (algorithms to be implemented)
- main.py # Sample flight data and test cases
