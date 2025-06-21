# CT_PYTHON_TASK2
A Python-based automated report generator developed as part of CodTech Internship Task-2. The program reads data from a CSV file, analyzes scores, and creates a well-formatted PDF report using FPDF. Designed to run smoothly on Google Colab.

🛠️ Tools & Technologies

- Python 3
- Pandas (for data handling)
- FPDF (for PDF generation)
- Google Colab (platform used)

---

## 📁 Files Included

| File Name     | Description                            |
|---------------|----------------------------------------|
| `data.csv`    | Input dataset with names and scores    |
| `report.pdf`  | Output PDF report (generated)          |
| `colab_code.ipynb` | Notebook with full working code   |

📊 What the Script Does

- Creates a CSV file with student names and scores (or uses an existing one)
- Calculates:
  - Average Score
  - Highest Score
  - Lowest Score
- Generates a clean and structured PDF report:
  - Title
  - Summary
  - Table of scores
- Downloads the report file
