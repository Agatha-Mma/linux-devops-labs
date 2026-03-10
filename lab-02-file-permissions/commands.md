# Commands Used in Lab 02

## View File Permissions

ls -l

## Create Test File

touch testfile.txt

## Change Permissions

chmod 755 testfile.txt

## Remove Write Permission

chmod u-w testfile.txt

## Add Execute Permission

chmod +x testfile.txt

## Change File Owner

sudo chown username testfile.txt

## Change Group Ownership

sudo chown :groupname testfile.txt
