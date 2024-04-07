This is a simple standalone implementation showing a a minimalistic RAG pipeline using models available in Gemini Pro API . Google AI Foundation lets developers to experience state of the art LLMs.
It uses connectors available in Langchain to build the workflow. 
This example leverages a simple Streamlit based UI and has a one file implementation. This example does not need any GPU to run.

Steps

1.Create a python virtual environment and activate it

python -m venv yourfolderpath\venv
source venv/bin/activate

2.Goto the terminal and execute below command to install the requirements

pip install -r requirements.txt

3.Create your Gemini_PRO_API Key https://ai.google.dev/.

Put your key in .env file

4.Run the example using streamlit

streamlit run index.py


