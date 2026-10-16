FROM jupyter/base-notebook:latest

WORKDIR ~/youtube_video/redis_project/docker_modules/

COPY requirements.txt /tmp/requirements.txt

RUN pip install --no-cache-dir -r /tmp/requirements.txt