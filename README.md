# gnuboard5-docker

base is wordpress    
https://github.com/docker-library/wordpress/tree/master/latest/php7.4/apache

docker build -t gnuboard-fpm-apache:1.0.0 .

docker-compose up -d

http://localhost:88/

Host : db    
User : gnuboard5    
Password : password    
DB : gnuboard5    

비밀번호 : password
