# Syllabus_oraganizer
# Syllabus Formatter

This Python script transforms a syllabus text file into a neatly formatted Word document (`.docx`). It’s perfect for students, educators, or anyone who wants to organize syllabus content with subjects, units, and topics.

## What It Does
- Takes a Markdown (`.md`) or plain text file as input.
- Creates a `.docx` file with:
  - Subjects as bold, centered headings.
  - Units (e.g., "UNIT 1:") as bold subheadings.
  - Topics with colons (e.g., "Topic:") italicized.
- Skips extra stuff like "Text Books," "Course Outcomes," or "References."

## How to Use It
1. **Get the Script**:
   - Download `syllabus_formatter.py` from this repository (click the file, then "Download" or clone the repo).

2. **Prepare Your Syllabus**:
   - Save your syllabus as a `.md` or `.txt` file.
   
3. **Run in Google Colab** (Recommended):
- Open [Google Colab](https://colab.research.google.com/).
- Upload `syllabus_formatter.py`:
- Go to `File > Upload notebook` or drag the file into a new cell.
- Run the script (Shift + Enter).
- Upload your syllabus file when prompted.
- Download the `.docx` file it generates.

4. **Run Locally** (Optional):
- Install Python 3 and the `python-docx` package:
```bash
pip install python-docx
