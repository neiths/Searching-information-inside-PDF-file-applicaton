# Searching-information-inside-PDF-file-applicaton
This is a Question and Answering app powered by Generative AI, utilizing the LaMini-T5-738M model available on Hugging Face. The Langchain library is employed to load a PDF file, which is then split into multiple chunks for processing.
The workflow involves using embeddings from a pre-trained model to convert text chunks into vectors. Subsequently, these vectors are stored in Chromadb.

install all the packages
```python
pip install -r requirements.txt

# run the app
streamlit run app.py
```


