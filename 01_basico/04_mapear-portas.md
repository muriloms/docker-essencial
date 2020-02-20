## Criar um novo container e expor a porta 80
`docker container run -p 8080:80 nginx`

## Visualizar os processos que estão ativos
`docker container ps`

## Acessar a porta 8080 em outro terminal
`curl http://localhost:8080`
### no browser acessar mesma porta para visualizar container ativo
