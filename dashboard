Documentation
https://docs.microsoft.com/en-us/troubleshoot/azure/virtual-machines/troubleshoot-ssh-connection

#SSHD is a daemon aka Linux Process -sshd

#Default port is 22

#configuration file
```cat /etc/ssh/sshd_config```

#log file / for ubuntu /var/log/auth.log
```tail -f /var/log/secure```

#another good log 
```cat /var/log/messages | grep -i sshd```

#check the status, can be restarted also 
```systemctl status sshd```

#running processes
```ps -eaf | grep -i sshd```


#listening ports
```lsof -Pi TCP | grep sshd```

#open ports
```netstat -a | grep -i ssh```

![image](https://user-images.githubusercontent.com/65220400/109195759-98b05680-77a3-11eb-962c-e453574a2a4d.png)

#check for open ports 
```nmap -Pn ipaddress```

![image](https://user-images.githubusercontent.com/65220400/109195724-8a623a80-77a3-11eb-8e77-6db8699cc690.png)

![image](https://user-images.githubusercontent.com/65220400/109197195-60117c80-77a5-11eb-85d3-d66f79f569a4.png)

![image](https://user-images.githubusercontent.com/65220400/109199039-a36cea80-77a7-11eb-99a9-89ca266b11ad.png)

![image](https://user-images.githubusercontent.com/65220400/109200219-057a1f80-77a9-11eb-9b8a-d25e28d79dc6.png)

#Solution ```chmod 711 sshd```
