# OpenVpn_-X-A-12

## Install the OpenVPN Client Export Utility package as follows:

```
    Navigate to System > Packages

    Locate the OpenVPN Client Export package in the list

    Click + Install next to that package listing to install
```


## on specifie les utilisateurs qui vont se connecter a l'openVpn 

on va configurer donc le backend en  choisissant le type Local User Access (cree localement les utilisateur dans le pfsense)


## creating a certificate authority with which we could certify server and users on the server


## setting the genral Server information 
```
interface is set to LAN
Local Port is set to 1194 
```

## Setting up cryptographical information 
```
here we would enable authentication on TLS packages
generate TLS authentication keys

```


## tunnel setting
 
```
setting up the tunnel ip address
setting up the local ip address
PS : you have to choose two different IP addressing range

```

## creating a certificate authority


## adding the rules 

```
when you check Firewall Rule you added a rule to permit connections to  openVpn server from internet everywhere on internet
when you check Firewall Rule you added a rule to permit connections to  openVpn server from clients -> internet 
when you check OpenVpn Rule you clients connection to pass through the tunnel
```


## creating the user ceritificate and final touch

```
- creating the user certificate 
- import it to the pfsense

==> a success message indicate the attribution of an ip address in the corresponding range previously specified 
```


