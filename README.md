# Arquitetura de Software Aplicada
## Project Aero

### Objetivo:
1. Criar um simples projeto Back-end de uma Companhia Aérea para realizar a consulta de voos e venda de passagens.
2. Criar uma imagem de um container UBUNTU, instalar os componentes necessários para a aplicação.
3. Rodar o container, disponibilizando a porta 5000 para consumir as API's.

### Rodando Projeto:
1. Acesse o CMD/SHELL na pasta raiz e rode o comando ``docker-compose up`` para iniciar o projeto.
3. Importe o arquivo `ProjectAero.postman_collection.json` no Postman para consumir as API's do projeto.

### OBS:
1. Caso seja necessário, acesse o banco de dados através da URL: ``http://localhost:5000/h2-console/`` utilizando as seguintes credenciais:
    1. Url: ``jdbc:h2:mem:aerocompany``
    2. Username: ``sa``
    3. Password: ``password``

2. Os arquivos presentes na pasta ``app-java`` serve somente para consulta, não é necessário utiliza-los para subir o projeto.

### Projeto Desenvolvido por:
1. Gabriel Cardoso - 11811ECP008
2. João Barboza - 11811ECP005
3. Alan Nicolas - 12011ECP025
