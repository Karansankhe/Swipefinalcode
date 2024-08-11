# Document Information Extractor

Welcome to the **Document Information Extractor**! This application allows you to extract essential details from PDFs or images and compile them into a downloadable PDF report using Google Gemini's generative AI model.

## Features

- **PDF Upload:** Upload one or more PDF files to extract customer details, product details, and total amounts.
- **Image Upload:** Upload an image file for analysis, which will be processed to extract relevant details.
- **PDF Creation:** Generate a downloadable PDF report with the extracted information.

## Installation

To run this application locally, you'll need to set up a Python environment and install the required packages. Here's how you can do it:

1. **Clone the Repository:**

    ```cmd
    git clone <repository-url>
    cd <repository-directory>
    ```


2. **Install the Dependencies:**

    ```cmd
    pip install -r requirements.txt
    ```

3. **Create a `.env` File:**

    Create a file named `.env` in the root directory of the project and add your Google API key:

    ```plaintext
    GOOGLE_API_KEY=your_google_api_key
    ```

4. **Run the Application:**

    ```cmd
    streamlit run main.py
    ```

## Usage

1. **PDF Upload:**
    - Click on the "Choose PDF files..." button to upload one or more PDF files.
    - The app will process each PDF and extract the required details.
    - Click "Analyze PDFs" to view the extracted information.
    - Download the analysis results as a PDF using the "Download Analysis PDF" button.

2. **Image Upload:**
    - Click on the "Choose an image..." button to upload an image file.
    - The app will analyze the image and extract the relevant details.
    - Click "Analyze Image" to view the extracted information.
    - Download the analysis results as a PDF using the "Download Analysis PDF" button.

## Requirements

- Python 3.x
- Streamlit
- Pillow
- PyMuPDF
- ReportLab
- `google.generativeai` (Python client for Google Generative AI)


![diagram-export-11-8-2024-8_34_11-pm](https://github.com/user-attachments/assets/5d1a94c9-282b-4521-b36a-90c66ec70fd9)
