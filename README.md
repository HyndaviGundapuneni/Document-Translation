# PDF Translator App

The **PDF Translator App** allows users to upload a PDF document, select a target language, and have the content of the PDF translated in real-time. Built using **Streamlit**, **PyPDF2**, and **Google Translate API**, this app provides an intuitive way to translate PDF documents into various languages.

## Features

- **PDF Upload:** Allows users to upload PDF documents for translation.
- **Language Selection:** Users can select the target language for translation.
- **Real-Time Translation:** The app translates the content of each page of the PDF document using the **Google Translate API**.
- **Translated Content Display:** The translated content of each page is displayed on the Streamlit interface.

## Requirements

To run this app, you need to install the following Python libraries:

- `streamlit`
- `PyPDF2`
- `googletrans`

You can install these libraries using `pip`:

```bash
pip install streamlit PyPDF2 googletrans
How to Run
Clone this repository or download the necessary files.

Install the required libraries as mentioned above.

Run the following command to start the Streamlit app:

bash
Copy code
streamlit run app.py
Open the app in your web browser (usually at http://localhost:8501).

Usage
Upload a PDF File: Click the "Upload PDF" button to upload a PDF file from your device.
Select the Target Language: Choose the language to which you want to translate the content of the PDF from the dropdown menu.
View Translated Content: The app will display the translated content of each page in the selected language.
Supported Languages
The app currently supports the following languages for translation:

Hindi
Spanish
French
German
Chinese
More languages can be added by modifying the language_options dictionary in the code.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Google Translate API: Used for translating the text in the PDF document.
PyPDF2: A Python library to extract text from PDF files.
Streamlit: A framework for building interactive web applications with Python.
csharp
Copy code

This `README.md` provides details on how to set up, use, and run your PDF Translator app. You can modify the language list or add more features as needed.






