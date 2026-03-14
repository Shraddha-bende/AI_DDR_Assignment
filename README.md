# AI_DDR_Assignment
Automated Detailed Diagnostic Report (DDR) Generator using Python — extracts inspection and thermal data, generates professional client-ready DDR report.
# AI DDR Report Generator

## Overview
This project generates a **Detailed Diagnostic Report (DDR)** automatically by analyzing inspection and thermal reports in PDF format. The system extracts textual data and thermal images, identifies impacted areas, and produces a structured Word report ready for submission or client presentation.

---

## Features
- Extracts text from inspection and thermal PDF reports
- Automatically extracts thermal images
- Detects impacted areas (e.g., Bedroom, Parking, Bathroom)
- Rule-based issue detection and severity scoring
- Handles missing or unclear information (marked as "Not Available")
- Generates a professional DDR report in Word format

---

## Technologies Used
- Python
- Libraries:
  - `pdfplumber` – PDF text extraction
  - `PyMuPDF` – PDF image extraction
  - `python-docx` – Word report generation

---

## Project Structure
