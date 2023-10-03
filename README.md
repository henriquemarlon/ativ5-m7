# Ativ5-m7

Saída esperada após execução do programa:

[***Vídeo Demo***](https://www.loom.com/share/e3ffaaa774c740efbf75e75bc98bc8a8?sid=8e88cb83-d2b0-4ac2-95ee-cd0e44fa64a1)

## Descrição:

- Foi utilizado para cumprir a tarefa foi utilizado um ec2 t3.large configurado apenas com uma instalação de docker engine e com ip elástico. Além disso, támbém utilizamos um RDS configurado com um banco postgres.

### Backend:

- Para o backend foi utilizado fastapi junto com o sqlalchemy, pycaret e pandas para fazer o fluxo de predição, login, cadastro e vicualizações de gráficos. A imagem resultante foi subida no docker hub: 

https://hub.docker.com/repository/docker/henriquemarlon/ativ5-m7-backend/general

### Frontend:

- Para o frotend foi utilziado warp um framework de rust para servir aplicações frontend, ao final a imagem tbm foi subida no docker hub:

https://hub.docker.com/repository/docker/henriquemarlon/ativ5-m7-frontend/general

### AWS:

-  Na AWS rodamos os comandos para dar pull nas imagens e o comando para rodar o backend (porta 8080) e o frontend (porta 3000).
