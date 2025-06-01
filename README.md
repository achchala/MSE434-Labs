# MSE 434 - Operations Research

This repository contains the lab assignments and projects for MSE 434 (Supply Chain Management) course.

## Team Members

- Achchala Deepan - 20943939
- Manjary Muruganandan - 20950662

## Project Structure

- `Lab1/`: Contains the first lab assignment focusing on optimization problems using IBM's CPLEX through docplex
- `requirements.txt`: Python package dependencies

## Setup Instructions

1. Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Unix/macOS
   # or
   .venv\Scripts\activate  # On Windows
   ```

2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Dependencies

- jupyter==1.0.0
- notebook==7.0.7
- docplex==2.25.236
- ipykernel==6.29.3
- openpyxl==3.1.2

## Note

These projects use IBM's CPLEX optimization solver through the docplex Python package.