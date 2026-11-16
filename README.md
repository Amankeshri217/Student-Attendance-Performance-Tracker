# Student Attendance \& Performance Tracker 

This project analyzes student attendance and marks from a CSV file to calculate attendance percentage, identify students at risk, and present the results with charts.

## Features

* **Auto-generates** dummy data (`students.csv`) if it doesn't exist on the first run.
* Computes accurate attendance percentages and average marks using Pandas.
* Robust data cleaning handling boundary conditions and invalid rows gracefully.
* Visualizes the outcomes using Matplotlib (Bar chart for attendance \& Scatter chart for attendance vs. marks).

## Prerequisites

Install the required libraries before running:

```bash
pip install -r requirements.txt
```

## How to Run

Run the Python script in your IDE (like Spyder/VS Code) or terminal:

```bash
python tracker.py
```

