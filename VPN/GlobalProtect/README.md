# Global Protect

Diferentes versiones del cliente de Globalprotect para GNU/Linux.

[Download and Install the GlobalProtect App for Linux](https://docs.paloaltonetworks.com/globalprotect/5-3/globalprotect-app-user-guide/globalprotect-app-for-linux/download-and-install-the-globalprotect-app-for-linux)

# Commandos
## Version
Para saber la versión de globalprotect que estamos utilizando podemos utilizar el comando
```
❯ globalprotect show --version
GlobalProtect: 5.3.3-4
Copyright 2009-2022 Palo Alto Networks, Inc.
```
## Conexion a una VPN
Para conectarnos a una VPN vamos a utilizar el comando
```
❯ globalprotect connect --portal <url> --username <username>
Disconnecting...
Retrieving configuration...
Discovering network...
Connecting...
Connected
```
## Desconexion a una VPN
Para conectarnos a una VPN vamos a utilizar el comando
```
❯ globalprotect disconnect
Disconnecting...                                                       
Disconnected                                                           
GlobalProtect status: Disconnected
```
## Detalles de una conexion
Para conectarnos a una VPN vamos a utilizar el comando
```
❯ globalprotect show --details
Gateway Name: <url:port>                                  
Gateway Description: GW_SSL
Assigned IP Address: <IP_Address_Client>
Gateway IP Address: <IP_Address_VPN>
Gateway Location: 
Protocol: SSL
Uptime(sec): 44
```
