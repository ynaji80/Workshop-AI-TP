# Launch Chatbot Application

## Pre-requisites
- Python and pyvenv (or Python3)
- API KEY for Cohere LLM (https://dashboard.cohere.com/)
- API KEY for Pinecone  (https://app.pinecone.io/)
- Name of your Pinecone index
- Name of your Pinecone environment of your index

## Steps  
1. Create Python virtual environment
    ```
    python3 -m venv {name of your venv}
    ```
    Or
    ```
    python -m venv {name of your venv}
    ```
    
2. Activate virtual environment
    ```
    source {name of your venv}/bin/activate
    ```

3. Install requirements 
    ```
    pip install -r requirements.txt
    ```

4. Configure .env file
    - Add Cohere API key
    - Add Pinecone API key
    - Add Pinecone environment of your index
    
5. Launch Jupyter Notebook
    ``` 
    jupyter notebook
    ```
