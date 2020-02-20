## Mapear diretórios na máquina host para o container
### Criar um diretório ex-volume/html
### na pasta html criar o arquivo index.html
### no diretório ex-volume executar o comando:
`docker container run -p 8080:80 -v $(pwd)/html:/usr/share/nginx/html nginx`
