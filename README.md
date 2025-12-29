# CCNA Cheatsheet

# Day 4:
```
enable
configure terminal
enable password <password> (pas secure)
service password-encryption
enable secret <password> (secure)
no <command>
show running-configuration
show startup-configuration
copy running-configuration startup-configuration
```

# Day 6:
```
arp -a (via console)
show mac address-table
clear mac address-table dynamic (possibilité de filtrer un peu + genre address <mac>, interface <iface>...)
```

# Day 8:

```
show ip interface brief
interface g0/0
ip address 10.0.0.1 255.255.255.0
no shutdown
show interfaces g0/0
show interfaces description <----- commande qui n'existe plus ?
description ## To SW1 ##
```

## Nombre magique:

```
200.15.10.32/27
255.255.255.224
256-224=32
0 32 64

Adresse réseau: 200.15.10.32
Première adresse dispo: 200.15.10.33
Dernière adresse dispo: 200.15.10.62
Brodcast: 200.15.10.63

Nombre d'hosts:
IPv4 = 32 bits - 27 (le masque de sous réseau) = 5
2 puissance 5 = 32 adresses (-2 pour adresse réseau et brodcast) = 30 adresses
```

# Day 9:

```
show interfaces status
speed 100
duplex full
interface range f0/5 - 12
interface range f0/5 - 8, f0/12 - 13
```

