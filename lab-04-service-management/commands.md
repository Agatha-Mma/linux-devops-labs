# Commands Used in Lab 04

## Check Status of a Service

systemctl status ssh

## Start a Service

sudo systemctl start ssh

## Stop a Service

sudo systemctl stop ssh

## Restart a Service

sudo systemctl restart ssh

## Enable Service at Boot

sudo systemctl enable ssh

## Disable Service at Boot

sudo systemctl disable ssh

## View All Running Services

systemctl list-units --type=service

## Check if Service is Enabled

systemctl is-enabled ssh
