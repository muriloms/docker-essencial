# Image build

#### Criar diretorio
#### Criar aquivo com nome:
Dockerfile

### Inserir instruções no documento
- exemplo:

```
FROM  nginx:latest 
RUN echo '<h1>Hello World !</h1>' > /usr/share/nginx/html/index.html`
```

#### No terminal roda o comando de build
docker image build -t ex-simple-build .

#### Construir bild
docker container run -p 80:80 ex-simple-build
