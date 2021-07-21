# recover-password-Windows
If you get Locked out, and your root /OS Disk is NOT encrypted, you can use: `chntpw`

## Works!
https://opensource.com/article/18/3/how-reset-windows-password-linux


alt:
- https://www.online-tech-tips.com/computer-tips/how-to-use-linux-to-reset-a-windows-password/


# function:
## listUsers()
```listUsers(){
cd /mnt/Microsoft/Windows/System32/config
chntpw -l SAM
}
```

sch: https://www.google.com/search?q=windows+change+password+from+linux
