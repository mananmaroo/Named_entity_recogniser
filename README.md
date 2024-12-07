Entity Extractor Pro
Extract and visualize named entities from PDF documents using Python's SpaCy and PyMuPDF.

📋 Project Overview
Entity Extractor Pro is a Python-based project designed to extract named entities from PDF documents and visualize them using SpaCy. The tool reads through each page of a PDF, processes the text for entity recognition, and allows interactive visualization of the results.

🚀 Features
Extracts named entities such as names, dates, organizations, and more from PDF files.
Utilizes SpaCy's powerful en_core_web_lg model for accurate entity recognition.
Processes multi-page PDFs seamlessly.
Provides an intuitive visualization of entities using SpaCy's DisplaCy.

🛠️ Technologies Used
Python: Main programming language.
SpaCy: For natural language processing and named entity recognition.
PyMuPDF (fitz): For reading and extracting text from PDF documents.
python-docx: (Optional) Future scope to handle DOCX files for similar processing.

🗂️ Project Structure
Input: A user-provided PDF file.
Process:
Extract text from each page using PyMuPDF.
Apply SpaCy's NLP pipeline to identify named entities.
Store extracted entities in a structured format.
Output:
A list of named entities with their types.
Interactive visualization of entities in Jupyter Notebook using DisplaCy.

🧑‍💻 How to Use
Install Required Libraries:
pip install spacy PyMuPDF python-docx
python -m spacy download en_core_web_lg
Run the Script:
Save the code as entity_extractor.py.
Execute the script in a Python environment:
python entity_extractor.py
Enter the path to the PDF file when prompted.
Visualize Results:
Open the output in a Jupyter Notebook to view the entity visualization using DisplaCy.



🤝 Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request with your improvements.
