# Shell

使用前
```
apt-get install -y xz-utils openssl gawk file
```
```
yum install -y xz-utils openssl gawk file
```
使用
```
wget https://raw.githubusercontent.com/xieruan/Shell/master/AutoReinstall.sh && bash AutoReinstall.sh
```

```
wget https://mirror.ghproxy.com/https://raw.githubusercontent.com/xieruan/Shell/master/AutoReinstall.sh && bash AutoReinstall.sh
```

dd centos硬盘空间变小

```
yum install cloud-utils-growpart -y
```

```
growpart /dev/vda 1
```

```
 resize2fs /dev/vda1
```
