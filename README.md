# Resume_Screening
Resume Screening App
Resume Screening App is a machine learning-powered tool designed to classify resumes into specific job categories. It utilizes TF-IDF Vectorization, SVM Classifier, and Streamlit for an interactive user interface.

Features
File Support: Upload resumes in PDF, DOCX, or TXT format.
Text Extraction:
Extract text from resumes using libraries like PyPDF2, python-docx, and built-in file handling.
Text Cleaning:
Preprocesses resume text to remove URLs, hashtags, mentions, special characters, and extra spaces.
Machine Learning:
Predicts job categories using a pre-trained SVM classifier.
Utilizes TF-IDF vectorization and Label Encoding for feature extraction and classification.
Interactive UI:
Built with Streamlit for seamless user experience.
Jupyter Notebook:
Includes Resume_Screening.ipynb for an exploratory and step-by-step implementation of the resume screening process.
Example Output
App Interface:

Upload a resume in PDF, DOCX, or TXT format.
The app extracts text and predicts a job category.
Example:

Uploaded Resume: Software Engineer Resume
Predicted Category: IT
Dependencies
The project uses the following Python libraries:

streamlit: For creating the user interface.
scikit-learn: For machine learning models (TF-IDF, SVM, Label Encoding).
PyPDF2: For extracting text from PDF files.
python-docx: For extracting text from DOCX files.
jupyter: For running the Jupyter Notebook.
