# Commands Used in Lab 01

## Create Project Directories
mkdir -p ~/project/app/logs ~/project/config ~/project/scripts

## Navigate to Directory
cd ~/project/app

## Create Files
touch index.html style.css app.py README.md config.json

## List Files
ls -la

## Move File
mv config.json logs/

## Copy File
cp README.md ../config/

## Create Backup
cp -r ~/project ~/project-backup-$(date +%Y%m%d)

## Install Tree Utility
sudo apt update
sudo apt install tree -y

## Show Directory Structure
tree ~/project
