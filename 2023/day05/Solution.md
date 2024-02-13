1. movie{1..20} <br>
```console
#!/bin/bash

for (( i=$2; i<$3; i++))
do
        mkdir $1$i
done
```

5. Creating 2 user
```console
sudo useradd user1
sudo useradd user2
```
```console
#below command is to just display the username
ubuntu@ip-172-31-18-155:~$ awk -F':' '{print $1}' /etc/passwd |tail -n 2
```
