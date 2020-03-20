Capture 1
La commande curl indique le nom du serveur et une adresse en IPv4.
Le numéro du port source pour joindre internet est 39246. 
Le numéro de paquet de la couche Application est à la ligne 70. 
Le paquet qui commence est 39246 à la ligne 67 et celui qui termine est 8003 à la ligne 78.

Capture 2
La commande dig fait un diagnostique du serveur DNS, il indique la même adresse en IPv4 que la commande curl. 
Il y a une transactions DNS avec question et réponse. Et une seconde en ARP avec question et réponse. 
La question posé en ARP est "qui est 192.168.1.254 ?". 
Les questions sont posé à tous les ordinateurs.
