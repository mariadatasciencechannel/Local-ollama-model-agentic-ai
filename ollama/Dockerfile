FROM ollama/ollama:latest

WORKDIR ~/youtube_video_code/redis_project/docker_modules/

ENV OLLAMA_HOST=0.0.0.0
RUN ollama serve & \
    sleep 5 && \
    ollama pull llama3.2




