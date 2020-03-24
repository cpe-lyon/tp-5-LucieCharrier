# CR ADMIN SYSTEME TP5 
### Jean-Baptiste BLAISE
### Lucie CHARRIER
### 25 mars 2020

## Exercice 1 : Adressage IP (rappels)
\ | Première adresse | Dernière adresse configurée | Adresse de broadcast
--- | --- | --- | --- 
Sous-réseau 1 : 38 machines | 172.16.0.1/26 | 172.16.0.38/26 | 172.16.0.63/26
Sous-réseau 2 : 33 machines | 172.16.0.65/26 | 172.16.0.98/26 | 172.16.0.127/26
Sous-réseau 3 : 52 machines | 172.16.0.129/26 | 172.16.0.181/26 | 172.16.0.191/26
Sous-réseau 4 : 35 machines | 172.16.0.193/26 | 172.16.0.228/26 | 172.16.0.255/26
Sous-réseau 5 : 34 machines | 172.16.1.1/26 | 172.16.1.34/26 | 172.16.1.63/26
Sous-réseau 6 : 37 machines | 172.16.1.65/26 | 172.16.1.102/26 | 172.16.1.127/26
Sous-réseau 7 : 25 machines | 172.16.1.129/27 | 172.16.1.154/27 | 172.16.1.159/27

## Exercice 2 : Préparation de l'environnement
On utlise le tableau proposé dans le sujet du TP pour configurer _serveur_ et _client_.<br>
_Serveur_ devant avoir une connexion internet et servire de passerelle, on lui attribut deux adapter : un mode NAT (VM > Hôte) et un mode réseau interne (VM1 <> VM2).<br>
_Client_ devant avoir un accès internet uniquement via le serveur, on lui attribut un seul adapteur : un mode réseau interne (VM1 <> VM2).<br>
On vérifie sur chacune des deux VM avec `ip -4 a`.<br>


## Exercice 3 : Installation du serveur DHCP

## Exercice 4 : Donner un accès à Internet au client

## Exercice 5 : Installation du serveur DNS

## Exercice 6 : Configuration du serveur DNS pour la zone tpadmin.local

## Exercice 7 : Installation d'un serveur web

## Exercice 8 : Installation d'un serveur de temps
