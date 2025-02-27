1.	https://youtu.be/bw-bMhlhcpg
2.	After installing docker on your system, run `docker –version`
3.	Open docker, and keep that window open t
4.	Once that is successfully done, create a new folder for the workshop.
5.	In your terminal navigate to that directory and create a file requirements.txt and copy the following contents into it. 

`langchain
langchain-community
langchain-core
chromadb
faiss-cpu
pypdf
beautifulsoup4
python-dotenv
ollama
sentence-transformers
wikipedia
arxiv
langchainhub
sentence_transformers
PyPDF2
langchain-objectbox
groq
cassio
fastapi
uvicorn
sse_starlette
python-dotenv`

6.	Now in the same directory run `python -m venv venv`
7.	Run `pip install -r requirements.txt`
8.	Run `docker run -d --name ollama -p 11434:11434 ollama/ollama`
9.	Run `docker exec -it ollama ollama pull nomic-embed-text`
10.	Run `docker exec -it ollama ollama pull llama2`
Steps 8, 9, 10 will download large docker images. Its important for the workshop.
