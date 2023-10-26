На сервере скопировать зашифрованный файл /tmp/nautilus.txt.gpg с хоста docker в контейнер ubuntu_latest (работающий на том же сервере) в расположение /home/. Не пытайтесь каким-либо образом модифицировать этот файл.

## Решение 
`docker cp /tmp/nautilus.txt.gpg ubuntu_latest:/home/`
