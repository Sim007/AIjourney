#Docker
DockerHub: https://hub.docker.com/r/ollama/ollama 
docker run -d -v ollama:/root/.ollama -p 11434:11434 --name ollama ollama/ollama
docker exec -it ollama ollama run llama3
docker exec -it ollama ollama run deepseek-r1

