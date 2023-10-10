# interact_with_pdf

This project allows you to upload a PDF document and extract its text content. Additionally, you can ask questions about the content of the PDF file, and the system will provide answers using a pre-trained language model.
## Prerequisites

Make sure you have the following libraries installed:

- torch
- streamlit
- PyPDF2
- transformers (Hugging Face Transformers)

## About the Code

- The code uses the PyPDF2 library to extract text from the uploaded PDF document.

- It utilizes the Hugging Face Transformers library and the DistilBERT model fine-tuned on the SQuAD dataset for question answering.

- The Streamlit framework is used to create a user-friendly interface for uploading PDFs and asking questions.
