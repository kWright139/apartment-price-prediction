# Apartment Rental Price Prediction

## Course
CAP4770 – Data Mining

## Project Overview
This project focuses on predicting apartment rental prices across the United States using machine learning techniques. The dataset includes property characteristics, location data, and listing information to analyze factors influencing rental prices.

---

## Team Members
- Member A — Data & Infrastructure Lead
- Member B — Analysis & Visualization Lead
- Member C — Modeling & Reporting Lead

---

## Repository Structure
notebooks/ → Jupyter notebooks for analysis
README.md → Project documentation

---

## Dataset
The dataset is stored in a shared Google Drive folder due to file size limitations.

### Files:
- apartments_for_rent_classified_10K.csv
- apartments_cleaned.csv (generated after preprocessing)

### Instructions:
1. Download the dataset from Google Drive  
2. Place the CSV file in the same directory as the notebook  
3. Run the notebook normally  

Google Drive Link: (https://drive.google.com/drive/folders/1rB2psfR9vEt5cAuxbeGVPt_cxslffQgK)

---

## Database Setup
The dataset is loaded into a SQLite database within the Jupyter Notebook using Python’s `sqlite3` library.

- A database file (`apartments.db`) is created locally when the notebook is executed  
- Data is inserted into a table and retrieved using SQL queries  

Note: The database file is not stored in this repository.

---

## Setup Instructions
To run this project locally:

1. Clone or download this repository  
2. Download the dataset from Google Drive  
3. Place the dataset in the same folder as the notebook  
4. Open the notebook in Jupyter  
5. Run all cells  

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- SQLite  

---

## Key Features
- Data cleaning and preprocessing  
- Handling missing values  
- Outlier detection and filtering  
- Exploratory Data Analysis (EDA)  
- Visualization of rental trends  

---

## Notes
- Large data files are stored externally in Google Drive  
- The notebook will automatically generate the SQLite database when executed  
