Progress Summary of Real dataset of Sales and Their dashboard Walmart database on online dataset


✅ Cleaned CSV loaded and verified (no nulls, correct dtypes)
✅ SMTP email alert for high sales is working
# Walmart Sales API Project

This project is built using **FastAPI** to expose Walmart sales data through RESTful APIs.

## 📂 Features

- `GET /` → Welcome message (status check)
- `GET /sales` → Returns full cleaned sales data
- `GET /high_sales` → Returns records where Weekly_Sales > 50,000

## 📊 Sample Dataset

Due to GitHub’s file size limit (100 MB), the full dataset `Walmart.csv` is not uploaded.  
Instead, a smaller file `sample_walmart.csv` with limited rows is provided for testing.

If needed, full data can be shared via external link (e.g., Google Drive or email).

## ▶️ How to Run This API

Make sure you have Python and FastAPI installed.

### 1. Install requirements
```bash
pip install -r requirements.txt
```

### 2. Run the app using Uvicorn
```bash
uvicorn app:app --reload
```

### 3. Test the API in browser or Postman
- http://127.0.0.1:8000/
- http://127.0.0.1:8000/sales
- http://127.0.0.1:8000/high_sales

## 📝 Files in This Repository

| File Name            | Purpose                              |
|----------------------|---------------------------------------|
| `app.py`             | Main FastAPI application              |
| `sample_walmart.csv` | Sample data for testing API           |
| `requirements.txt`   | Required Python packages              |
| `README.md`          | Project documentation (this file)     |

## ✅ Created for Internship Submission

This project is part of my internship submission task focused on API development and data handling using Python.

s

Next Steps:
1. Connect Power BI to Walmart_Cleaned.csv
2. Load cleaned data into PostgreSQL
3. Update Power BI data source to API 
