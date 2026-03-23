# Atividade 1.1 Avaliativa de 2026.1 - 1o Bimestre - Sistemas operacionais - Mateus Rocha Lucas da Silva

## Introdução:
A atividade consiste na criação, configuração e execução de uma aplicação Django dentro de uma imagem fedora disponibilizada pelo professor através de um repositório no Github.
## Relato das atividades:
Após adicionar o repositório disponibilizado a minha conta pessoal criei a pasta app e dentro dessa pasta criei o arquivo requiremets.txt:<br>

![criação app](./imagens/criacao_app.png) <br>

Criei um arquivo dockerfile.dev e construi e executei o container:<br>

![criação docker](./imagens/build_docker.png) <br>
![execução docker](./imagens/run_docker.png) <br>

Dentro do container criei o projeto Django, criei uma aplicação e adicionei essa aplicação ao settings.py, executei as migrações do banco de dados e criei : <br>

![aplicação django](./imagens/aplicacao_django.png)
![app ao settings](./imagens/webapp.png)

Criei uma view simples com o meu nome, configurei a URL da aplicação e executei o servidor e testei a aplicação pelos links: http://localhost:8000 , http://localhost:8000/admin:

![view](./imagens/view.png)
![url](./imagens/url.png)
![localhost](./imagens/localhost.png)
![admin](./imagens/admin.png)
## Considerações finais:
