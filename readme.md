1) Скачать директорию и перейти в нее
2) В терминале выполнить команды:
  docker build -t my_nginx .
  docker run --name my_nginx-server -d -p 80:80 my_nginx
