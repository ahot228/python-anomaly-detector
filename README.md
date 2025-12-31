# Python Anomaly Detector 

## Data Validation Mini Project

A Python tool to validate CSV datasets for missing values, duplicates, schema mismatches, and outliers using Pandas, with automated tests via unittest and PyTest.

Pandas for Validation:
 
• Detect and fill missing values.
• Validate and convert data types.
• Filter invalid entries.

Data Checks:

• Count/drop duplicates.
• Validate schema (columns + types).
• Detect outliers (IQR).

Testing:

• Write tests for nulls, duplicates, schema.
• Run with:
pytest or
python3 -m unittest

Features:

• Reads CSV → validates → outputs summary (text).
• Detects:
   • Missing/duplicate records
   • Schema mismatches
   • Invalid/non-numeric entries
   • Outliers
