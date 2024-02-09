# Launch  Workshop

## Pre-requisites
- Python and pyvenv (or Python3)
- API KEY for Cohere LLM (<https://dashboard.cohere.com/>)
- API KEY for Pinecone (<https://app.pinecone.io/>)
- Name of your Pinecone environment of your API KEY

## Create Cohere API KEY
You can get one by signing up <https://app.cohere.io/dashboard>. Visit the Cohere dashboard to retrieve your API key. If you haven't previously connected a session, you should see it in the main screen. Otherwise, you can find it in the settings page.

## Create Pinecone API KEY
Follow the instructions in this video: <https://youtu.be/_gC9wWWBjmY?si=Z06gAoH7miIhoEKk>

## Steps for Unix/Linux/MacOS and Windows
1. Create Python virtual environment
    - For Unix/Linux/MacOS:
        ```
        python3 -m venv {name of your venv}
        ```
        Or
        ```
        python -m venv {name of your venv}
        ```
    - For Windows:
         ```
        python3 -m venv {name of your venv}
        ```
        Or
        ```
        python -m venv {name of your venv}
        ```

2. Activate virtual environment
    - For Unix/Linux/MacOS:
        ```
        source {name of your venv}/bin/activate
        ```
    - For Windows:
        ```
        {name of your venv}\Scripts\activate
        ```
    
    You should see the name of your environment on the command prompt or terminal.

3. Install requirements
    ```
    pip install -r requirements.txt
    ```

4. Configure .env file
    - For Unix/Linux/MacOS:
        ```
        cp .env.example .env
        ```
    - For Windows:
        ```
        copy .env.example .env
        ```
    
    - Add Cohere API key
    - Add Pinecone API key
    - Add Pinecone environment of your index
    
5. Launch Jupyter Notebook

Be sure to launch under your python environment. You should see the name of your environment on the command prompt or terminal
    ``` 
    jupyter lab
    ```

Note: Replace `{name of your venv}` with the name you want to give to your virtual environment.

Note: Replace `{name of your environment}` with the name of your Pinecone environment.

Note: Replace `{your-cohere-api-key}` and `{your-pinecone-api-key}` with your respective API keys.
