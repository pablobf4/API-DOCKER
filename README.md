# API-DOCKER

1. Criar a imagem Docker
 - docker build -t pb-projeto-docker-api .


2. Testar a imagem localmente
 - docker run -p 8080:80 pb-projeto-docker-api


3. Subir a imagem para um registro público Faça login no Docker Hub
 - docker login

4- Renomeie a imagem com seu repositório do Docker Hub:
 - docker tag pb-projeto-docker-api <SEU_USUARIO_DOCKERHUB>/pb-projeto-docker-api:latest

5- Renomeie a imagem com seu repositório do Docker Hub:
 - docker tag pb-projeto-docker-api <SEU_USUARIO_DOCKERHUB>/pb-projeto-docker-api:latest

6- Envie a imagem para o Docker Hub:

 - docker push <SEU_USUARIO_DOCKERHUB>/pb-projeto-docker-api:latest

7- Compartilhe o nome da imagem com seu para quem precisar:

- docker pull <SEU_USUARIO_DOCKERHUB>/pb-projeto-docker-api:latest
- docker run -p 8080:80 <SEU_USUARIO_DOCKERHUB>/pb-projeto-docker-api:latest



Imagem : https://hub.docker.com/r/pablobf4/pb-projeto-docker-api



  

		
