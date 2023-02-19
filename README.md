# PocketMine-MP Installation for Termux
PocketMine-MP Installation for Termux

Make sure you're using the lastest version of Termux by downloading on [F-Droid](https://f-droid.org/en/packages/com.termux/) or [Github](https://github.com/termux/termux-app/releases)

WARNING: This script is free to use, and we don't copy from [get.pmmp.io](https://get.pmmp.io). Please don't do false report for their repository!
# Installation
Step 1: Update & Upgrade Packages
```bash
pkg update && pkg upgrade -y
```
Step 2: Install some dependencies packages
```bash
apt install jq curl wget getconf -y
```
Step 3: use this command + create new directory to using as pmmp folder then run the script below
```bash
mkdir pmmp 
cd pmmp
curl -sL https://raw.githubusercontent.com/crischutu07/pmmp-installation-termux/main/install.sh | bash -s -
bash start.sh
```
# Demo Installation
[![asciicast](https://asciinema.org/a/560881.svg)](https://asciinema.org/a/560881)
