# context-responsive-chatbot-using-llma3-
this is my graduation project





1- create a virtual env using conda or venv that contains python 3.9 

2-install the libraries running this command 
"pip install -r cookbook/llms/ollama/rag/requirements.txt"

3-you  must have ollama and docker desktop running on your pc.
run the command ("ollama run llama3")
if u have the model it will run if u dont it will download automatically. estimated size 4.7 gb
the run the commnds in "run_pgvector.sh" after initiating docker 
u ll see that the database image is initialized on docker and it is all set up 
to test the project 
run the command "streamlit run cookbook/llms/ollama/rag/app.py"


u will notice there are other choices for llms u can use give it a try and choose the model u desire. 
