# document-chatbot
a question-answering chatbot using mxbai-embed-large for embeddings and an LLM with Retrieval-Augmented Generation (RAG). built with gradio, it answers only questions relevant to the provided document

## setup:
- `pip install -r requirements.txt`
- add enviroment variable `GOOGLE_API_KEY=<api_key>`
- paste your documents (any type) into the `./data` folder
- run `ollama pull mxbai-embed-large`
- run `python document_qa.py`

## screenshot:
![screenshot](images/screenshot.png)

