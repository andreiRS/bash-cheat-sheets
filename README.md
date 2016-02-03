# bash-cheat-sheets

##Show file permision 
```
#show file permision in digital format (Ex: 644 not -rw-r--r--)
##OSX: 
stat -f "%p %N" *
##linux
stat -c "%a %n" *
```

## Generating a new SSH key
```
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
# Creates a new ssh key, using the provided email as a label
Generating public/private rsa key pair.
```
