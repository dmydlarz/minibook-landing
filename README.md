```
PORT=80
main folder -> public
caddy http server

docker build -t minibook-nginx:latest .
docker run --name minibook-nginx -p 8080:80 minibook-nginx:latest
```