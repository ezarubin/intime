first commit Развернул вм с убу сервером. установил докер docker pull 
nginx cd / склоинровал репо и создал файл mkdir repo git clone 
https://github.com/ezarubin/intime.git cd intime nano index.html Hello 
World запустил nginx с пробросом порта и добавлением волюма своей репо 
где лежит штмл. docker run --name lesson1 -p 8080:80 -v 
/repo/intime:/usr/share/nginx/html nginx после запуска вместо страници 
приветсвия nginx
 Hello World
