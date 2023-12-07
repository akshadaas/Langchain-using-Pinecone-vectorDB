# Langchain

Any information that could be recent, proprietary or domain-specific, is fed to LLM model in the form of PDF. The data present in the pdf is divided into smaller chunks. OpenAI embeddings are used to convert this chunks into vectors. Then these vectors are stored in the vectorDB (here, pincone).  

When we fetch a query , it gets converted into embeddings and then similarity search is applied between query vector and vectors present in vectorDB. 

## How to run?
## STEPS

### STEP 0: Clone the repository
```bash
git clone https://github.com/akshadaas/Langchain-using-Pincone-vectorDB.git
```
### STEP 1: Create virtual environment (windows)
```bash
python -m venv [env_name]
[env_name]\Scripts\activate
```
### STEP 2: Install requirements
```bash
pip install -r requirements.txt
```

