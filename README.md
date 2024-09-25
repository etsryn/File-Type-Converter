# File-Type-Converter-FTC

# Project Title
File Type Converter

# Description
**File Type Converter**, this Streamlit-based web application allows users to seamlessly convert between different file formats, including DOCX to PDF, PDF to CSV, and image-to-PDF conversions (JPEG, PNG, JPG). The application is designed to be user-friendly, fast, and reliable.

# Installation (Method 1)
1. Download `.zip` file for this project under `Code` option button on Repository Page
2. Extract the `.zip` file to your preferred location
3. Open any Integrated Development Environment IDE of your choice on extracted folder's location, i used `VS Code` as IDE
4. Install the neceesary libraries if not installed earlier
   Use Command :
   ```bash
   pip install -r requirements.txt
   ```

   Or Update if already installed but not updated
   Use Command :
   ```bash
   pip install --upgrade -r requirements.txt
   ```
   # Installation (Method 2)
1. Open any Integrated Development Environment IDE of your choice on a location where you wish to store the project, i used `VS Code` as IDE
2. Clone this `.git` repository
   Use Command :
   ```bash
   git clone https://github.com/your-username/file-type-converter.git
   ```
3. Install the neceesary libraries if not installed earlier
   Use Command :
   ```bash
   pip install -r requirements.txt
   ```

   Or Update if already installed but not updated
   Use Command :
   ```bash
   pip install --upgrade -r requirements.txt
   ```

# Usage
Since this project is a `streamlit`-based web application, so simply `py ftc.py` won't help to execute this program, instead use
   ```bash
   streamlit run ftc.py
## Features

- Convert **DOCX to PDF**
- Convert **PDF to DOCX**
- Convert **PDF to CSV**
- Convert **CSV to PDF**
- Convert **PDF to JPEG/JPG/PNG**
- Convert **JPEG/JPG/PNG to PDF**

## Demo

You can run the application locally using Streamlit. Here's how to get started.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.7 or above
- Streamlit
- Pillow
- PyMuPDF (also known as `fitz`)
- Pandas
- `docx2pdf`
- `pdf2docx`
- `pdf2image`
- ReportLab

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/file-type-converter.git
