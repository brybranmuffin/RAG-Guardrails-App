# CS10 RAG Chatbot

This repository contains a Jupyter notebook that implements a Retrieval-Augmented Generation (RAG) chatbot specifically designed for CS10 course content. The chatbot utilizes OpenAI embeddings, Pinecone vector database, and LlamaIndex for document retrieval.

## Prerequisites

Before running this notebook, you'll need:

1. **API Keys:**
   - OpenAI API key (for embeddings and LLM)
   - Pinecone API key (for vector database)

2. **Python Environment:**
   - Python 3.8+ recommended (Python 3.9 or 3.10 is optimal for compatibility)
   - Jupyter Notebook or JupyterLab

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/brybranmuffin/RAG-Guardrails-App.git
   ```

2. Set up a Python environment (recommended):
   ```bash
   cd chatbot
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install IPython kernel:
   ```bash
   python -m ipykernel install --user --name=cs10-chatbot
   ```

4. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```


## Running the Notebook Locally

To run the Jupyter notebook, follow these steps:

1. **Activate the Python Environment:**
    Make sure you are in the `chatbot` directory and activate your virtual environment:
    ```bash
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

2. **Launch Jupyter Notebook:**
    Start the Jupyter Notebook server:
    ```bash
    jupyter notebook
    ```

3. **Open the Notebook:**
    In your web browser, navigate to the Jupyter interface and open the notebook file (e.g., `application.ipynb`).

4. **Run the Cells:**
    Execute the cells in the notebook sequentially. Make sure to run any setup cells before running the main code cells.

5. **Interact with the Chatbot:**
    Follow the instructions in the notebook to interact with the RAG chatbot and test its functionality.

6. **Stop the Jupyter Server:**
    Once you are done, you can stop the Jupyter server by pressing `Ctrl+C` in the terminal where it is running.

## Running the Application in Google Colab

To run the application in Google Colab, follow these steps:


1. In your web browser, navigate to the Google Colab interface
2. upload the application.ipynb file to Google Colab
3. recreate the file structure in the left panel by clicking the folder icon and navigating to the files in the repo

    root
    |
    |-- application.ipynb
    |-- data
    |   |-- cs10_lecture_notes.pdf
    |   |-- cs10_policies.pdf
    |   |-- ...
    |-- config
    |   |-- rails
    |   |   |-- guardrails.json
    |   |-- config.yml
    |   |-- prompts.yml
    |-- loaded_data
3. run the notebook on colab





