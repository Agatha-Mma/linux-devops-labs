# Commands Used in Lab 06

## Create a New User

sudo useradd devuser

## Set Password for User

sudo passwd devuser

## Switch to the User

su - devuser

## Check User ID Information

id devuser

## Create a Group

sudo groupadd devgroup

## Add User to Group

sudo usermod -aG devgroup devuser

## View Groups of a User

groups devuser

## Delete a User

sudo userdel devuser

## Delete a User and Home Directory

sudo userdel -r devuser
