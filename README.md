# PDF Information Retrieval Application
Welcome to the Searching Information Inside PDF File Application! This app leverages Generative AI, specifically the LaMini-T5-738M model available on Hugging Face, to power its Question and Answering (QA) capabilities. The Langchain library facilitates the loading of PDF files, which are then segmented into smaller chunks for efficient processing.

# Features
- Generative AI: Utilizes the LaMini-T5-738M model for advanced question answering.
- PDF Processing: Langchain library is employed to load PDF files and split them into manageable chunks.
- Embedding Conversion: Converts text chunks into vectors using embeddings from a pre-trained model.
- Chromadb Integration: Stores vectors in Chromadb for efficient retrieval and indexing.

# Model Details
- LaMini-T5-738M: A powerful Generative AI model with 738 million parameters, capable of handling complex question answering tasks.
- Model Size: 8GB

# Installation
To install all the required packages, simply run the following command:

```Python
pip install -r requirements.txt
```

# Usage
Once all the packages are installed, you can run the application using Streamlit:

```Python
streamlit run app.py
```

# How to Use
- Upload a PDF file using the app interface.
- Enter your query/question in the provided input box.
- Click on the "Search" button to retrieve relevant information from the PDF.
- View the generated answers and navigate through the document chunks.

# Conclusion
The PDF Information Retrieval Application offers a convenient way to search for information within PDF documents using advanced Generative AI techniques. By harnessing the power of LaMini-T5-738M and integrating with Langchain and Chromadb, the app provides efficient and accurate question answering capabilities, making it a valuable tool for researchers, students, and professionals dealing with large volumes of textual data.


