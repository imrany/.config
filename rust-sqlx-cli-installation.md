# Rust sqlx-cli crate (postgres drivers)
Run 
```bash
cargo install sqlx-cli
```
## Proceed below if you get an error
```bash
sudo apt update
sudo apt install openssl libssl-dev
```
if you get problem when installing `libssl-dev`
```bash 
cd etc/apt
sudo nano sources.list
```
then add this line
```
deb http://ftp.de.debian.org/debian sid main
```
then save and run
```bash 
sudo apt update
```
after updating run
```bash 
cargo install sqlx-cli
```
