# Python Anomaly Detector 

## Data Validation Mini Project

A Python tool to validate CSV datasets for missing values, duplicates, schema mismatches, and outliers using Pandas, with automated tests via unittest and PyTest.

Quick Python Essentials:

• Read/write CSV files (csv, pandas).
• Define reusable functions.
• Handle errors with try / except.
Practice: Read CSV → return shape → compare schemas.

Pandas for Validation:
 
• Detect and fill missing values.
• Validate and convert data types.
• Filter invalid entries.
Practice: Fill missing ages → ensure salary is float → validate ranges.

Data Checks:

• Count/drop duplicates.
• Validate schema (columns + types).
• Detect outliers (IQR).

Testing:

• Write tests for nulls, duplicates, schema.
• Run with:
pytest or
python -m unittest discover

Features:

• Reads CSV → validates → outputs summary (text/JSON).
• Detects:
   • Missing/duplicate records
   • Schema mismatches
   • Invalid/non-numeric entries
   • Outliers
