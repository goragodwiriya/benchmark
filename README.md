#ดาวน์โหลด docker file
```docker pull goragod/kotchasan```

#รัน
```docker run -i -t goragod/kotchasan```

#start apache
```service apache2 restart```
เปิดบราวเซอร์ เรียก http://172.17.0.2

#start mysql
```service mysql restart```
http://172.17.0.2/phpmyadmin
username : root
password : 1234
หรือ
username : plus
password : 1234

#start ssh
```service ssh restart```
สามารถ ssh เช้าไปยัง Server ได้
IP : 127.17.0.2
Port : 22
username : root
password : 1234
