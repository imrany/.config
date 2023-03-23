## To install nodejs in linux
First uninstal the current nodejs that comes with the linux os with
```bash
sudo apt remove nodejs
```

Go to [https://nodejs.org/en/download](https://nodejs.org/en/download)

Download the node version you want node-v14.x it will downloas as a `nodev-14.x-linux-x64.tar.gz`
then extract the folder by running
```bash
tar -xf node-v14-linux-x64.tar.gz
```
run `ls` to list the contents

move the folder's content to `~/nodejs` in the home directory by running

```bash
mv node-v14-linux-x64 ~/nodejs
```
navigate to `~/nodejs` and list contents
on the home dir `~/`
open `.bashrc` with nano
```bash
nano .bashrc
```
at the very bottom type 

`export PATH=$PATH:/home/imrany/nodejs/bin`

save the file with `Ctrl + S` and exit with `Ctrl + X`
close the terminal
open and new terminal and run

```bash
node -v
```
