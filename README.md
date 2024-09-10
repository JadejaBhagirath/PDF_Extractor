# PDF Text Extractor

A simple Python script to extract text from a PDF file and save it as a plain text file. This tool utilizes the `PyMuPDF` library (also known as `fitz`) for efficient text extraction from PDF documents.

## Features

- Extracts text from each page of a PDF.
- Saves the extracted text to a `.txt` file.
- Handles different text encodings and complex layouts.

## Prerequisites

Before running the script, make sure you have the following installed:

- Python 3.x
- `PyMuPDF` library

You can install the necessary libraries using:

```bash
pip install PyMuPDF

Clone the Repository:

bash

git clone https://github.com/yourusername/pdf-text-extractor.git
cd pdf-text-extractor

Place Your PDF File: Place the PDF file you want to extract text from in the root directory of the repository.

Run the Script: Update the file path in the script and run it using:

bash

python extract_text.py

Make sure to update the path to your PDF file in the script:

python

pdf_path = r'C:\path\to\your\PDF\file.pdf'

Check the Output: The extracted text will be saved in a file named extracted_text.txt in the same directory.
