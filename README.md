# meng-lanbo.github.io
[toc]
## 1.获取SSH
```
apt install openssh -y
echo -e "password\npassword" | passwd
```
## 2.备份
```
mkdir -p /tmp/mybackup/
dd if=/dev/mtd9 of=/tmp/mybackup/mtd9
```

## 3.更改环境变量

