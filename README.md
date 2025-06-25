# intro 
- this is a Naive RAG pipeline (indexing-retrieval-generation) using OpenAI API 
- vector store: chromadb
- embedding model: openai embedding model
- dataset to retrieve is in ./news_articles 
# install environment 
all the code is run on linux 
```
python -m venv venv 
source venv/bin/activate 
pip install -r requirements.txt
```
you put your OPENAI_API_KEY in file .env

# usage 
run 
```
python app.py
```