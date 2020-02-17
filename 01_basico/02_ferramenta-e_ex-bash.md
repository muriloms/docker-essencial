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
