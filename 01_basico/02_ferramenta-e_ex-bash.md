### Compreender como o container utiliza o bash do sistema
- exercutar `bash --version`
- executar `docker container run debian bash --version`

### Visualizar containers ativos 
`dcoker container ps`

### Visualizar todos os container que foram executados
`docker container ps -a`

### Executar container e depois remover
`docker container run --rm debian bash --version`

### O método "run" sempre cria um novo container
#### Para comprovar, executar os seguintes comandos:
- Criar um novo container e entrar no modo iterativo no terminal do container
`docker container run -it debian bash`
- Criar um documento
`touch curso-docker.txt`
- Conferir
`ls -la`
- Sair
`exit`
- Criar novo container (comando igual ao de cima) e verificar (`ls -la`) se existe o arquivo "curso-docker.txt
