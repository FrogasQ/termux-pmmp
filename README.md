# Termux PMMP
Create PocketMine-MP Server on Termux Mobile.
Download Termux on PlayStore!

# Setup Step by Step!
- [Update & Upgrade Package](https://github.com/FrogasQ/termux-pmmp/blob/main/README.md#update--upgrade-package)
- [Install GIT](https://github.com/FrogasQ/termux-pmmp/blob/main/README.md#install-git)
- [Allow Permission Dandied](https://github.com/FrogasQ/termux-pmmp/blob/main/README.md#allow-permission-dandied)
- [Setup & Start Server](https://github.com/FrogasQ/termux-pmmp/blob/main/README.md#setup--start-server)
- [Read This](https://github.com/FrogasQ/termux-pmmp/blob/main/README.md#notes)
# Update & Upgrade Package
```bash
> pkg update -y && pkg upgrade -y
```

# Install GIT
```bash
> pkg install git
```
```bash
> git clone https://github.com/FrogasQ/termux-pmmp
```
```bash
> cd termux-pmmp
```

# Allow Permission Dandied
```bash
> chmod +x setup.sh
```
```bash
> chmod +x start.sh
```
```bash
> cd pmmp/bin/php7/bin
```
```bash
> chmod +x php
```
```bash
> cd $HOME/termux-pmmp/pmmp
```
```bash
> chmod +x run.sh
```
```bash
> cd $HOME/termux-pmmp
```

# Setup & Start Server
```bash
> ./setup.sh
```
<b>If you want to start the server again then use the command:</b>
```bash
> ./start.sh
```

# Notes
<b>This server running PocketMine-MP for minecraft bedrock 1.16.200! Can't work for minecraft bedrock 1.16- or 1.16+</b>




