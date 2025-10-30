# JMANsTools
PDFTools&amp;img

# PDF to PPTX Converter

A lightweight desktop tool to convert one or multiple PDF files into PPTX slides.  
Built with Tkinter, `pdf2image`, and `python-pptx`.

## Why
I wanted a fast and reproducible way to turn PDFs into editable slides without manual copy & paste.

## Features
- Pick multiple PDFs and convert them in one go
- Progress indicator and status messages
- 600 DPI rendering for crisp slides
- Auto-fits each page image to the slide canvas (no margins)

## Requirements
- Python 3.9+  
- Poppler (required by `pdf2image`) installed and available on `PATH`
  - Windows/macOS/Linux users: install Poppler for your OS and make sure the `bin` folder is on your `PATH`.

Install Python packages:
```bash
pip install -r requirements.txt

