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


#PHP info
http://127.17.0.2/info.php

#การทดสอบ benchmark บนเครื่องตัวเอง
```sh /var/www/html/php-framework-benchmark/benchmark.sh```

เบื่องต้นผมให้ทดสอบด้วยตัวเองได้รายการเดียวคือ Loading Performance (PHP5.6) ใครทดสอบแล้วได้ผลเป็นยังไงแชร์กันดูบ้างนะครับ

ไฟล์เว็บไซต์ทั้งหมดอยู่ที่ ```/var/www/html``` สามารถ ssh เข้าไปดูได้ครับ
