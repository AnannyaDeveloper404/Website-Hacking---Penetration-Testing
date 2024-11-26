# Website hacking --- Penetration testing :

---

## Website :

**Website** is a **web application** installed in a **server** and Server is simply just a **computer**

## Web Server :

It's basically an application that you can install on any computer ans the computer doesn't have to be exposed to the internet.It specifies a certain location within your file system ans in that location you can host files so anybody connected to the same network will be able to access those files.

### Websites files

web application ,executive server ,php ,python

- Web application interacts with database to display items,products etc.

## Metasploitable machine

A target machine

- username:msfadmin
- password:msfadmin
- ip:192.168.182.129

- Get access to the IP address of target machine <ifconfig>
- Search the IP address in browser which will display the web application
  The webserver here is Metasploitable and application being hosted are mutilidae,dvdw,phpmadmin etc.

## How to access websites:

- An application on a computer -> web application -> Pentesting
- Computer users on OS + other application -> server side attacks .
- Managed by humans -> client side attacks

### Information Gathering :

- IP addressing
- Domain name info
- Technologies used
- other websites on the same server
- DNS records
- Unlisted files , sub-domains ,dimension

## Interception of exploitable files //Metasploitable

- Go to **Metaploitable** ip address via browser(keep Metasploitable vm open).
- In **Burpsuite** ,turn on the **intercept** of **proxy** setting.
- Now make change in the proxy server which will allow us to upload exploitable files in the web server.
- Uploading will depend on the web application's security level-
