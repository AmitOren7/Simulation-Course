# Hotel Simulation Project

## Overview

This project models a **hotel with various facilities** using **event-based simulation**. The goal is to analyze customer behavior, queue times, and hotel ratings based on different factors. Through statistical analysis, we examine aspects such as **check-in and check-out processes**, **facility usage**, and **alternative management strategies** to optimize hotel performance.

## Features

- **Event-Based Simulation**: Models hotel operations including customer arrivals, departures, and facility usage.
- **Customer Behavior Modeling**: Tracks guest movements, facility visits, queue wait times, and satisfaction ratings.
- **Queue Analysis**: Evaluates bottlenecks, especially at peak hours (e.g., breakfast rush).
- **Statistical Analysis**:
  - Check-in and check-out distribution
  - Facility usage trends
  - Impact of delays on hotel ratings
  - Comparative analysis of alternative management strategies
- **Optimization Strategies**: Tests alternative policies (e.g., staff improvements, facility expansions) to enhance hotel efficiency and ratings.

## Simulation Components

The project includes various classes to model hotel operations:

- **Customer**: Represents an individual guest, tracking their queue patience and satisfaction rating.
- **Group**: A collection of customers with shared reservations and activities.
- **Room**: Hotel rooms with different sizes, availability, and pricing.
- **Hotel**: Manages all rooms, customer check-ins, check-outs, and overall hotel rating.
- **Facilities**:
  - **Reception**: Handles check-in and check-out processes.
  - **Bar**: Includes pricing for different drinks and customer choices.
  - **Pool & Spa**: Models operating hours and customer usage.
  - **Breakfast**: Analyzes customer flow and seating constraints.

## Key Findings

- **Queue Bottlenecks**: The breakfast queue created a major issue due to peak-hour congestion.
- **Hotel Rating Factors**: Customer ratings were affected by **waiting times** more than **food quality**.
- **Alternative Strategy Testing**:
  - Upgrading kitchen staff improved **food quality but had minimal impact** on customer ratings.
  - Queue optimization strategies (e.g., staggered breakfast times) **showed more promise** for improving ratings.

## Requirements

To run the simulation, install the following dependencies:

```bash
pip install pandas numpy scipy matplotlib sympy openpyxl enum34
```

If you are using Google Colab, you may also need:

```bash
pip install google-colab
```

### Libraries Used:
- **pandas** – Data manipulation
- **numpy** – Numerical operations
- **scipy** – Statistical analysis & optimization (`scipy.stats`, `scipy.optimize`, `scipy.integrate`)
- **matplotlib** – Visualization
- **sympy** – Symbolic mathematics
- **openpyxl** – Excel file handling
- **enum** – For defining enumerations
- **datetime** – Handling timestamps
- **heapq** – Priority queue management
- **random** – Random number generation
- **contextlib** – Context management
- **IPython.display** – For displaying results in notebooks

## Running the Simulation

1. **Run all import statements** to ensure dependencies are loaded.
2. **Execute the 'Statistics Tests for Check In and Out distribution' section** to analyze the check-in and check-out behavior.
3. **Upload an Excel file** containing hotel data when prompted.
4. **Run the remaining simulation steps** to complete the analysis and optimization.

## Conclusion

This simulation provides **data-driven insights** for hotel management. The key takeaway is that **reducing wait times (especially for breakfast) improves customer ratings more effectively than improving food quality**. This study suggests that hotels should **focus on queue management strategies** before investing in expensive kitchen upgrades.
