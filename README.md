### Material:
- [Aula 19.1](https://app.betrybe.com/course/live-lectures/sd-cohort-21-b#aula-191-introducao-a-docker)
- [Aula 19.2](https://app.betrybe.com/course/live-lectures/sd-cohort-21-b#aula-192-docker-utilizando-containers)
- [Aula 19.3](https://app.betrybe.com/course/live-lectures/sd-cohort-21-b#aula-193-orquestrando-containers-com-docker-compose)

### Preparação:
- [ ] Rodar uma imagem docker - Aula 19.1 tempo 00:59:00 - 01:03:20
- [ ] Listar imagens locais - Aula 19.1 tempo 01:03:25 - 01:03:52
- [ ] Interagir com container - Aula 19.1 tempo 01:07:55 - 01:13:10
- [ ] Reiniciar containers - Aula 19.1 tempo 01:16:00 - 01:17:50
- [ ] Contexto Dockerfile - Aula 19.2 tempo 00:15:20 - 00:24:24
- [ ] Criando um Dockerfile - Aula 19.2 tempo 00:28:52 - 00:35:00
- [ ] Builder um Dockerfile - Aula 19.2 tempo 00:35:00 - 00:40:10
- [ ] Contexto sobre redirecionamento de ports de container - Aula 19.2 tempo 00:46:00 - 00:57:24
- [ ] Momento Rafa chateado - Aula 19.2 tempo 00:52:13 - 52:52
- [ ] Subindo container com redirecionamento de Port - Aula 19.2 tempo 00:59:00 - 01:06:30
- [ ] Criar Dockerfile do Trybe Wallet - Aula 19.2 tempo 01:07:52 - 01:19:20
- [ ] Criar network em Docker - Aula 19.3 tempo 00:09:18 - 00:28:06
- [ ] Contexto sobre Volumes Docker - Aula 19.3 tempo 00:33:23 - 00:37:28
- [ ] Trabalhando com volumes no Projeto App de Receitas - Aula 19.3 tempo 00:45:39 - 00:56:56
- [ ] Diferença entre ENTRYPOINT e CMD - Aula 19.3 tempo 00:58:50 - 01:01:50
- [ ] Contexto Docker Compose - Aula 19.3 tempo 01:07:42 - 01:28:00

### Guia de Bolso
![Guia-de-bolsa](https://user-images.githubusercontent.com/5350121/182646000-1e347a50-d257-45f5-affb-0f10ee4217dd.png)


### Requisitos
- [ ] Crie um container em modo interativo, sem rodá-lo, nomeando-o como `01container` e utilizando a imagem `alpine` na versão `3.12`
- [ ] Inicie o container `01container`
- [ ] Liste os containers filtrando pelo nome `01container`
- [ ] Execute o comando `cat /etc/os-release` no container `01container` sem se acoplar a ele
- [ ] Remova o container `01container`
- [ ] Faça o download da imagem `nginx` com a versão `1.21.3-alpine` sem criar ou rodar um container
- [ ] Rode um novo container com a imagem  `nginx` com a versão `1.21.3-alpine` em segundo plano nomeando-o como `02images` e mapeando sua porta padrão de acesso para porta `3000` do sistema hospedeiro
- [ ] Pare o container `02images` que está em andamento
- [ ] Gere uma build a partir do Dockerfile do `back-end` do `todo-app` nomeando a imagem para `todobackend`
- [ ] Gere uma build a partir do Dockerfile do `front-end` do `todo-app` nomeando a imagem para `todofrontend`
- [ ] Gere uma build a partir do Dockerfile dos `testes` do `todo-app` nomeando a imagem para `todotests`
- [ ] Suba uma orquestração em segundo plano com o docker-compose de forma que `backend`, `frontend` e `tests` consigam se comunicar
