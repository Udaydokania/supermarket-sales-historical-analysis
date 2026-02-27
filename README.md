# Supermarket Sales Historical Analysis 🛒📉

## 📌 Project Overview
This project provides a historical evaluation of supermarket sales performance using Python. The analysis focuses on uncovering seasonal trends, regional distribution, and shipping efficiency to understand the key drivers of revenue. By utilizing time-series resampling, the study breaks down performance into monthly and quarterly intervals to identify growth patterns and operational bottlenecks.

## 🛠 Tech Stack
- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Visualization:** Matplotlib
- **Environment:** Jupyter Notebook

## 📖 Data Dictionary
The analysis is based on a supermarket sales dataset with the following key attributes:
| Column | Description |
| :--- | :--- |
| **Order ID** | Unique identifier for each customer order. |
| **Order Date** | The date the transaction was placed (used for time-series analysis). |
| **Ship Mode** | The delivery method used (e.g., Standard Class, Second Class). |
| **Segment** | The customer category (Consumer, Corporate, Home Office). |
| **Region** | Geographic location of the sale (East, West, Central, South). |
| **Sales** | Total revenue generated for the specific transaction. |

## 🧹 Data Ingestion & Time-Series Preparation (Day 2 Update)
The second phase focused on auditing the dataset and preparing the temporal features for trend analysis:
- **Dataset Loading:** Successfully ingested the `SuperMarket sales record.csv` dataset, confirming a total of 18 features and 9,800 records.
- **DateTime Transformation:** Converted the `Order Date` column to a standard datetime format using `pd.to_datetime` to enable precise time-series resampling.
- **Data Integrity:** Conducted an initial inspection of the dataset using `.head()` and `.info()` to ensure data types were correctly assigned for numerical columns like `Sales`.
- **Filtering:** Isolated specific yearly data (e.g., 2018) to perform granular monthly and quarterly revenue tracking.

## 📂 Repository Structure
- `SuperMarket sales record.csv`: Raw historical sales dataset.
- `requirements.txt`: Project dependencies (Pandas, Numpy, Matplotlib).
- `.gitignore`: Standard Python exclusion rules.
- `README.md`: Project documentation and progress updates.
