# Dockerfile
FROM python:3.9-slim

# Instala o curl
RUN apt-get update && apt-get install -y curl

# Copia a aplicação
COPY app.py /app/app.py
WORKDIR /app

# Instala as dependências
RUN pip install Flask

# Executa a aplicação
CMD ["python", "app.py"]
