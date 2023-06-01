Я воспользовался следующими командами при выполнении лабораторной работы №2:

docker pull nginx
touch primer.html
apk update && apk add nan
nan primer.html
docker run -d -p 80:80 nginx
docker cp primer.html confident_faraday:/usr/share/nginx/html/primer.html
docker pull httpd
docker cp /local/path/to/your/primer.html confident_faraday:/usr/local/apache2/htdocs/primer.html
