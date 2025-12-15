# 📊 Job Postings Analysis Using API Data

## Description

This project fetches job posting data from a public API and analyzes it to determine:

* The number of job postings mentioning specific **technologies**
* The number of job postings available in specific **locations**

The analyzed results are displayed in the console and also exported to an **Excel file** for easy review and further analysis.

The project demonstrates practical usage of **Python**, **REST APIs**, **data processing**, and **Excel automation**.

---

## 🚀 Features

* Fetches real-world job data using an API
* Counts job postings by **technology skills** (e.g., Python, Java, SQL)
* Counts job postings by **location** (e.g., New York, Seattle, Austin)
* Exports results to an Excel file with separate sheets:

  * Technology-wise job count
  * Location-wise job count

---

## 🛠️ Technologies Used

* Python
* Requests
* Pandas
* OpenPyXL
* JSON
* REST API

---

## 📂 Project Structure

```
├── job_analysis.py
├── job-postings.xlsx
└── README.md
```

---

## 📈 Output

* **Console Output**

  * Technology-wise job count
  * Location-wise job count

* **Excel File (`job-postings.xlsx`)**

  * Sheet 1: Technology vs Number of Job Postings
  * Sheet 2: Location vs Number of Job Postings

---

## ▶️ How to Run

1. Clone the repository
2. Install required dependencies:

   ```bash
   pip install requests pandas openpyxl
   ```
3. Run the Python script:

   ```bash
   python job_analysis.py
   ```
4. Check the generated `job-postings.xlsx` file.

---

## 📌 Use Case

This project is useful for:

* Data analysis beginners
* Understanding API-based data extraction
* Learning how to automate Excel reports
* Job market trend analysis

---

## 📝 License

This project is for educational purposes.

## Author: Varrun Vashisht



