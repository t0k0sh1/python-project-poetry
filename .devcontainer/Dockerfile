FROM python:3.8.3-slim

RUN apt update && apt upgrade \ 
  && apt install -y \
  git \
  && pip install --upgrade pip && pip install poetry \
  && poetry config virtualenvs.in-project true