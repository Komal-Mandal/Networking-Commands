# Networking-Commands

### 1. The ping command checks if a computer or server is reachable by sending a small test message and measuring how long it takes to get a reply. It's like saying “Are you there?” and waiting for a “Yes” from the other side. In simple terms, it is used to check network connectivity between two devices, such as a computer and a server.

```
ping google.com
```
### 2. SSH (Secure Shell) is a network protocol that allows you to securely connect to another computer or server over the internet or network and control it remotely through the command line.

```
ssh username@hostname
```
### 3.netstat is used to display active internet connections, listening ports, and network protocols such as TCP and UDP. It helps monitor network activity and troubleshoot connectivity issues.

```
netstat
```
### 4.  ifconfig is used to view and configure network interfaces on Linux/Unix systems, such as Ethernet, local (loopback), Wi-Fi, and Docker virtual interfaces.

```
ifconfig
```
### 5. traceroute Used to trace the path packets take to reach a destination (like youtube.com) by showing each hop (router) along the way.

```
traceroute youtube.com
```
### 6. mtr is a combination of tracepath and ping.

```
mtr youtube.com
```
### 7. nslookup youtube.com – Retrieves the IP address(es) associated with youtube.com by querying the DNS server.

```
 nslookup youtube.com
```
### 8. telnet youtube.com 80 – Attempts to connect to YouTube’s server on port 80 
```
telnet youtube.com 80
```
### 9. ip address show: Displays all network interfaces along with their assigned IP addresses (IPv4 and IPv6) and other details like MAC address and interface status.
```
 ip address show
```
### 10.iwconfig is used to view or configure wireless network interfaces .It only works with wireless interfaces, not Ethernet.

```
iwconfig
```
### 11. The dig (Domain Information Groper) command is used to query DNS servers for information about domain names, like their IP addresses, name servers, and more.

```
dig youtube.com
```
### 12. whois is used to retrieve domain registration details such as the domain owner, registrar, creation/expiry dates, and contact information.

```
whois
```
