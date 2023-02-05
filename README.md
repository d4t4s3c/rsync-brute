# rsync-brute

**`rsync-brute` discovers hidden resources in `rsync` when the option is in mode `list = no` and we have no ability to list the resources.**

![](/01.png)

- <kbd>Download / Install</kbd>

```cmd
root@kali:~# wget -q "https://raw.githubusercontent.com/d4t4s3c/rsync-brute/main/rsync-brute" -O /usr/bin/rsync-brute
root@kali:~# chmod +x /usr/bin/rsync-brute
```

- <kbd>Use</kbd>

```cmd
root@kali:~# rsync-brute -t <TARGET> -w <WORDLIST>
```

---
