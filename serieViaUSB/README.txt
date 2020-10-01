serieViaUSB permet l'envoi de données du robot à l'ordinateur via USB.

Une fois que la carte mère peut communiquer avec le PC par le port USB, 
il faut tout de même avoir un programme qui peut aller lire et écrire les données 
sur ce port. Lorsqu'on programme la carte en utilisant la commande “make install”, 
l'utilitaire de chargement avrdude est appelé par une des règles du Makefile. 
Ce programme se charge d'ouvrir un canal de communication vers le port USB 
pour envoyer les données vers la carte. 
Par contre, 
lorsqu'on désire rediriger les données émises par RS232 vers le câble USB, 
il faut utiliser le programme serieViaUSB pour y arriver. 
Tout comme avrdude, serieViaUSB ouvre un canal de communication vers le port USB 
pour permettre les échanges de données. 
Il n'y a aucune licence associée à ce programme.

