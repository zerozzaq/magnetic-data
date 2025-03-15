# Magnetic Anomaly Data of the Eastern North Pacific

This repository contains magnetic anomaly data collected from the eastern North Pacific region. The data are intended to support geomagnetic navigation research.

## Data Description
- **Filename:** Magnetic anomaly data of the eastern North Pacific.csv
- **Format:** CSV (Comma Separated Values)
- **Fields:**
  - `lat` (float): Geographic latitude (degrees)
  - `lon` (float): Geographic longitude (degrees)
  - `magnetic anomaly` (float): Magnetic anomaly intensity (nT)

## Usage
This dataset can be loaded and analyzed using Python's `pandas` library.

```python
import pandas as pd

# Load the dataset
data = pd.read_csv('Magnetic anomaly data of the eastern North Pacific.csv')

# Display the first five rows
print(data.head())
