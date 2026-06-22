
# Latchup Trend Tool

This tool provides a GUI to process latchup Excel data and generate IV plots with pin-based color mapping and stage-based markers.

## Features

- Select Excel file
- Automatically detect node names
- Extract latchup data to CSV
- Plot IV curves
- Hover to display:
  - Pin
  - Voltage
  - Current
- Pin represented by colors
- Stage represented by marker shapes

## Requirements

Install required packages:

```bash
pip install -r requirements.txt

## How to Use

Run the GUI:

Shellpython app_gui.pyShow more lines
or double-click:
run_app.bat


Select Excel file
Click Process Excel
Select node
Click Plot

Notes

Pins without data will be shown as N/A
Excel files with format issues may need to be re-saved before use

Author
Eason.HS Liu
