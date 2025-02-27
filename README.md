1.	https://youtu.be/bw-bMhlhcpg
2.	After installing docker on your system, run `docker –version`
3.	Open docker, and keep that window open t
4.	Once that is successfully done, create a new folder for the workshop.
5.	clone this repo
6.	Now in the same directory run `python -m venv venv`
7.	Run `venv/Scripts/activate`
8.	Run `pip install -r requirements.txt`
9.	Run `docker run -d --name ollama -p 11434:11434 ollama/ollama`
10.	Run `docker exec -it ollama ollama pull nomic-embed-text`
11.	Run `docker exec -it ollama ollama pull llama2`
Steps 7, 8, 9 will download large docker images. Its important for the workshop.
