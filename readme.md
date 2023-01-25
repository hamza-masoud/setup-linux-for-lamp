# learn how to setup ubuntu 20 for LAMP
LAMP(Linux + Apache + MySQL/MariaDB + PHP)

## 1. setup server
first you need to get server to install this things on it
I recommended to get a server from digitalocean (price start from 4$ / MOTH)

### add ssh key 
1. run `ssh-keygen` to get new ssh key 
2. copy the public key (name.pub) and add it in the server 

## 2. install apache
you need to install apache first
1. run this code for update the server 
```
sudo apt update
```
2. run this command for install apache
```
sudo apt install apache2
```
