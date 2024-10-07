# LLM project to chat about Cricket :)
repository for the LLM zoomcamp project
# Cricket World Cup 
the data set is an HTML page https://en.wikipedia.org/wiki/2023_Cricket_World_Cup about the  Cricket World Cup
- Data is ingested using langchain_community.document_loaders lib AsyncHtmlLoader
- The flow and he evaluation are implemented in NoteBook : RAG_flow and Evaluation.ipynb
- The evaluation is performed using Ragas where a ground truth data is generated
- The evaluation is also shown by using LLM as a judge

# Technology
- LLM : OpenAI, Ollama
- Knowledge Base using FAISS from Facebook : https://github.com/facebookresearch/faiss
- Evaluation uses Ragas https://docs.ragas.io/en/stable/
- Interface is planned to use Streamlit

## Note for reviewers:
- clone the repo
  
    ``git clone ``
  - install the required libraries
    
  ``pip install -r requirements.txt``
