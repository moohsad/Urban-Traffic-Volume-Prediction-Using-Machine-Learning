# Urban Traffic Prediction

This project preprocesses traffic data from four junctions in Isfahan, Iran, to predict the hourly number of cars passing through, aiding urban traffic management.

## Overview
The dataset records hourly car counts at four junctions from May 2020 to December 2021. The goal is to engineer features and train a machine learning model to predict traffic volume accurately.

### Dataset
- **Source**: `traffic.csv` (place in `data/` directory)
- **Size**: 48,120 rows, 3 columns (initially)
- **Key Features**:
  - `DateTime`: Timestamp (Gregorian)
  - `Junction`: Junction ID (1-4)
  - `Car`: Hourly car count (target)

## Requirements
- Python 3.10+
- Libraries: `pandas`, `numpy`, `khayyam`, `lightgbm`, `scikit-learn`

Install dependencies:
```bash
pip install -r requirements.txt
