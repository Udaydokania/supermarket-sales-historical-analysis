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

## 📂 Repository Structure
- `requirements.txt`: Project dependencies (Pandas, Numpy, Matplotlib).
- `.gitignore`: Standard Python exclusion rules to maintain a clean workspace.
- `README.md`: Project documentation and overview.
