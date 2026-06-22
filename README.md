
# Latchup Trend Tool

This tool provides a GUI to process latchup Excel data and generate IV plots with pin-based color mapping and stage-based markers.

## How to Use
1. Download and unzip `LU_Trend_Tool.zip`
2. Open a terminal in the unzipped project root
3. Install required packages:
   ```bash
   pip install -r requirements.txt
   
Run the GUI:

double-click:
run_app.bat

- Select Excel file
- Click Process Excel
- Select node
- Click Plot

## Notes
- Pins without data will be shown as N/A
- Excel files with format issues may need to be re-saved before use
  
## Author
Eason.HS Liu

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
  
### Screenshots
- **GUI Interface**
<img width="564" height="526" alt="image" src="https://github.com/user-attachments/assets/1f6dbad6-c196-4613-a260-bca5c10e4255" />

- **Generated IV Plot**
<img width="1797" height="1001" alt="image" src="https://github.com/user-attachments/assets/e61dbb8a-f00d-438a-af81-0722aa03affc" />
<img width="1797" height="967" alt="image" src="https://github.com/user-attachments/assets/077601a9-dc25-4e5f-929e-b875a29af4e8" />
