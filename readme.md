В директории c html и Dockerfile в терминале выполнить команды:

1) docker build -t my_nginx .
2) docker run --name my_nginx-server -d -p 80:80 my_nginx
