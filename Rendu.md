1.	Exploration locale en solo

•	En ligne de commande

Nom, adresse MAC et adresse IP de l'interface Wifi

Nom: en0: 
	Adresse Mac : ether f0:18:98:29:6b:81 
	Adresse IP de l'interface Wifi : 10.33.1.119 


Nom, adresse MAC et Adresse IP de l'interface Ethernet
Pas de port Ethernet…


Adresse réseau : Adresse IP = 10.33.1.119
         Convertir en binaire : 00001010.00100001.00000001.01110111

Adresse réseau : Masque = 0xff000000
         Convertir en binaire : 11111111000000000000000000000000

Adresse réseau : Broadcast : 00001010.00100001.00000001.11111111

Adresse réseau : Gateway : 10.33.3.253

•	Affichez votre gateway

Une commande pour connaître l'adresse IP de la passerelle de votre carte Wifi : traceroute 12.34.56.78

•	En graphique (GUI : Graphical User Interface)
 



•	À quoi sert la gateway dans le réseau d'Ingésup ?
Un gateway est le nom générique d'un dispositif permettant de relier deux réseaux informatiques de types différents, par exemple un réseau local et le réseau Internet.



2.	Modifications des informations

A.	Modification d'adresse IP - pt. 1
Première adresse = adresse réseau + 1  
(00001010.00100001.00000001.01110111) +1
Dernière adresse = adresse réseau -1
(00001010.00100001.00000001.11111111)-1
                                                                                                           
Nmap
nmap -sn -PE 10.33.0.0/22
Résultat :
 


II. Exploration locale en duo

J’ai rencontré un souci avec la partie 2 (l’exploration locale) avec mon mac, car mon binôme nous avons  tous deux un macbooks de même série mais on a eu un soucis avec les adapteurs et le câble rj45... et il y aussi le fait de ne pas pouvoirs se voir pendant les vacances, je m’en excuse.
