# 📦 AI-Based Email Data Extraction for Logistics Quotes

This project automates the extraction of shipping quotations from `.eml` email files and uploads the parsed data into a Google Sheet, following a specified logistics format.

## 🚀 Features
- Parses `.eml` email files to extract:
  - Sender email and received date
  - Shipping line, origin and destination ports
  - 20GP / 40HC rates, ETD/Cutoff, and T/S info
- Uses BeautifulSoup for email content parsing
- Auto-updates data into Google Sheets via Google Sheets API
- Fully runnable in Google Colab (no local setup required)

## 📂 Files
- `extract_to_sheet.ipynb` – Main Colab notebook
- Sample `.eml` email files (not included due to privacy)
- `README.md` – This file
- 'log_file.png' showing how the extraction looks like

## 📄 How to Use
1. Open the notebook in Google Colab
2. Upload your `.eml` files and Google API credentials JSON
3. Run the notebook step-by-step
4. Data is automatically pushed to your linked Google Sheet

## 🔧 Requirements
- Python (Colab environment)
- `beautifulsoup4`, `google-api-python-client`, `google-auth`

## 🔗 Live Output
[Google Sheet Output (View Only)](https://your-output-sheet-link)

## 📬 Contact
**Author:** Anurag Singh  
**Email:** anuragsinghania45@gmail.com

---

> 🚫 Manual data entry was not used. Fully AI-powered solution as per task guidelines.
