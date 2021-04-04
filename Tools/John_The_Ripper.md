# John the Ripper

## create a new user name "Jack"
```
root@kali# useradd -r Jack
```
## set password for Jack, I used "123456"
```
root@kali# passwd Jack
New Password:
Retype New Password:
passwd: updated successfully
```

## in Linux, the passowrds are stored in "/etc/shadow", run john the ripper on "/etc/shadow"
```
root@kali# john /etc/shadow
```
