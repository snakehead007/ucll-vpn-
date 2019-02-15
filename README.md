# ucll-vpn
tunnelling using the leia.uclllabs.be
-----------------------------------------
**FOR LINUX**
version 0.4

HOW TO INSTALL
---------------
clone all files in a folder
```
apt-get install sshuttle
```
```
sh ./install.sh
```
To run the app:
```
ucll-vpn
```

Options for installation:
```
-v : verbose (more output)
-h : help message
```

NOTES
-----------
If you intent to use this to get internet at your exams, use an extra vpn behind it.
leia.uclllabs.be monitors all network traffic, with supervision in the exam-period
(you need to change the useragent of your browser too)

How to check your ip in the leia.uclllabs.be server for anonymity:
```
$ netstat -a | <YOUR_VPN_ADDRESS_HERE>
```
```
$ netstat -a | <YOUR_ACTUAL_IP_ADDRESS_HERE>
```
It should only find your vpn's ip address.
info: 
```
netstat -a
```
: shows all incoming and outgoing connections in the current server
```
| grep <IP_ADDRESS>
```
: finds your ip 
