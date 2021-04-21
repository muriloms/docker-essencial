### Na mesma pasta criada no arquivo anterior 
```docker container run -d --name ex-daemon-basic -p 8080:80 -v $(pwd)/html:/usr/share/nginx/html nginx```

### Stop container 
```docker container stop ex-daemon-basic```
