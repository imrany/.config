Working with repositories

Working with repositories may mean either of two different things:

    You can use a repository with the apt family of programs (apt, apt-get, apt-cache, aptitude) to browse or install packages
    You can set up a repository yourself and add, remove or replace packages in it. 

Using a repository

Using a repository is fairly simple: For the official Debian repository open /etc/apt/sources.list, insert the line
```bash
cd /etc/apt
sudo nano sources.list
```
then paste

 ```deb http://ftp.debian.org/debian stable main contrib non-free``` 
 
then save
then run

```bash
sudo apt update
```

(As the root user or using sudo of course). You might also consider to use a URL like: 


For more info check 

[https://wiki.debian.org/DebianRepository](https://wiki.debian.org/DebianRepository)
