# PDF Generator 📝

This is a Python script that automatically generates a multi-page PDF file using data from a CSV file.  
Each entry in the CSV creates a dedicated section in the PDF, with the topic name and a specified number of pages.

## 📌 How It Works

- Reads data from `example.csv`
- For each row:
  - Adds a new page with the topic title
  - Draws a line under the title
  - Adds additional blank pages (based on the `Pages` value)
  - Inserts the topic name in the footer of every page

## 📄 CSV Format

Make sure your `example.csv` file has the following structure:

```csv
Topic,Pages
Python,3
Data Science,2
Machine Learning,4
