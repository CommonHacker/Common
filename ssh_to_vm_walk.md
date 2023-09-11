# SSH into VM

### First open vm

##### You will sign into your VM and check your port status and check if ssh is running 

# *REMEBER* 
### Check, Change, Check

First you will use.. 

```

netstat -nato
```

then...

```

sudo systemctl status ssh.service 
```

If its not running then you'll use..

```

sudo system start ssh.service
```

##### Once its running you can use netstat -neto to check ssh port is open. 

# NEXT 

### Open up CMD if on windows. 

##### You will then ssh into vm from CMD by using 

```

ssh <username>@IP adresse 
```

## After you enter your password you have successfull ssh into your vm 

#### Now to double check port you can run 

```

netstat -natp 
```


