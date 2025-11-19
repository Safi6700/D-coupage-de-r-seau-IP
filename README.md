## Le réseau est en 172.16.1.0/24., on a donc les 4 sous-réseaux suivants :  
Le Pôle informatique (6 bureaux, environ 50 équipements au total)  
Le Pôle développement (6 bureaux, environ 12 équipements au total)    
Le Pôle Administratif (4 bureaux, environ 20 équipements au total)    
Le Pôle Technicien (4 bureaux, environ 15 équipements au total)    

## Le réseau est en 172.16.1.0/24., on a donc les 4 sous-réseaux suivants  

### Découpage symétrique:  

Sous-réseau 1: Pôle informatique  2^6=64 CIDR=32-6bits=26 donc CIDRE=26  
Adresse de réseau: 172.16.1.0/26  
Début de plage IP disponible:172.16.1.1  
Fin de plage IP disponible: 172.16.1.62  
Adresse de broadcast: 172.16.1.63  

Sous-réseau 2: Pôle développement  2^6=64 CIDR=32-6bits=26 donc CIDRE=26    
Adresse de réseau: 172.16.1.64/26  
Début de plage IP disponible: 172.16.1.65  
Fin de plage IP disponible: 172.16.1.126  
Adresse de broadcast: 172.16.1.127  

Sous-réseau 3: Administratif  2^6=64 CIDR=32-6bits=26 donc CIDRE=26   
Adresse de réseau: 172.16.1.128/26  
Début de plage IP disponible: 172.16.1.129  
Fin de plage IP disponible: 172.16.1.190  
Adresse de broadcast: 172.16.1.191  

Sous-réseau 4: Pôle Technicien  2^6=64 CIDR=32-6bits=26 donc CIDRE=26  
Adresse de réseau: 172.16.1.192/26  
Début de plage IP disponible: 172.16.1.193  
Fin de plage IP disponible: 172.16.1.254  
Adresse de broadcast: 172.16.1.255  

### Le découpage asymétrique:  
Sous-réseau 1: Pôle informatique 50EQ  2^6=64 CIDR=32-6bits=26 donc CIDRE=26    
Adresse de réseau: 172.16.1.0/26  
Début de plage IP disponible:172.16.1.1  
Fin de plage IP disponible: 172.16.1.62  
Adresse de broadcast: 172.16.1.63  

Sous-réseau 2: Administratif 20EQ 2^5=32 CIDR =32-5bits=27 donc CIDRE=27    
Adresse de réseau:172.16.1.64/27  
Début de plage IP disponible:172.16.1.65  
Fin de plage IP disponible:172.16.1.94  
Adresse de broadcast:172.16.1.95  

Sous-réseau 3: Pôle Technicien 15EQ  2^5=32 CIDR =32-5bits=27 donc CIDRE=27    
Adresse de réseau:172.16.1.96/27  
Début de plage IP disponible:172.16.1.97  
Fin de plage IP disponible:172.16.1.126  
Adresse de broadcast:172.16.1.127  

Sous-réseau 4: Pôle développement 12EQ  2^4=16 CIDRE=32-4bits=28 donc CIDRE=28  
Adresse de réseau:172.16.1.128/28  
Début de plage IP disponible:172.16.1.129  
Fin de plage IP disponible:172.16.1.142  
Adresse de broadcast:172.16.1.143  
