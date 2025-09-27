# Airbnb Hotel Booking Analysis
## Overview

This project presents an in-depth analysis of Airbnb hotel booking data, focusing on pricing, availability, and booking trends. The aim is to provide insights into factors influencing bookings, helping stakeholders make informed decisions.

## Objectives

Data Exploration: Understand the structure and content of the Airbnb dataset.

Data Cleaning: Handle missing values, duplicates, and inconsistencies.

Exploratory Data Analysis (EDA): Visualize distributions, correlations, and trends.

Key Insights: Derive actionable insights to inform business strategies.

 ## Tools & Libraries

- Python: Programming language for analysis.

- Pandas: Data manipulation and analysis.

- Matplotlib & Seaborn: Data visualization.

- NumPy: Numerical operations.

## Dataset

The dataset Airbnb_Open_Data.csv contains information on Airbnb listings, including:

- Listing ID

- Host ID and Name

- Neighborhood

- Room Type

- Price

- Number of Reviews

- Last Review Date

- Availability

## Key Findings

Price Distribution: Pricing patterns across neighborhoods and room types.

Availability Trends: Listing availability throughout the year.

Review Patterns: Number of reviews and ratings to gauge guest satisfaction.

 ## Getting Started
1. Running in Google Colab

   ```python import pandas as pd
   from google.colab import files
   #Upload CSV from your local system
   uploaded = files.upload()
   df = pd.read_csv("Airbnb_Open_Data.csv")
   ```

After running the cell, an upload button appears to select the CSV file.

2. Running in a Local Jupyter Notebook

 ```python import pandas as pd
 #Ensure the CSV is in the same folder as your notebook or provide full path
 df = pd.read_csv("Airbnb_Open_Data.csv", low_memory=False)
 df.head()
```


Tips:

If the file is in a different folder, use the full path:

```python
df = pd.read_csv("C:/full/path/to/Airbnb_Open_Data.csv", low_memory=False)
```

## 🔧 How to Run

Clone the repository:

git clone https://github.com/harshita-89/VOIS_AICTE_Oct2025_Harshita_Meena.git

Open the Jupyter Notebook or Colab Notebook:

jupyter notebook Airbnb_Hotel_booking_analysis.ipynb


## License

This project is licensed under the MIT License
