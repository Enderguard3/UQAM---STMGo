# Travail pratique 2 - StmGO

## Description

stmGO est un calculateur de trajet permettand de trouver le trajet le plus court (ou non) 
d'un point A à un point B (dans la limite de la base de donnée que l'on lui fourni).
Il tiens compte des horraires, et des stations intermédiaires si nécéssaire.

## Auteur

César Ombredane (OMBC91090108)

## Fonctionnement

Pour faire fonctionner le projet, aucune dépendances n'est nécéssaire.

- Rendez-vous dans le dossier contenant **tp2.pl** et **lignes.pl** avec votre invite de commande.
- entrez la commande : ``` swipl ``` pour entrer dans l'interpreteur prolog.
- charger le fichier **tp2.pl** a l'aide de la commande ``` ['tp2.pl']. ```
- executez ensuite la commande ``` stmGO. ``` pour lancer le programme.
- suivez ensuite les instructions comme dans l'exemple suivant.

(Attention : les stations et lignes disponibles sont uniquement celle contenues dans la base de donnée)

```prolog
------------------------------------------------------------------------
Bienvenue, ici votre itinéraire de transports publics
------------------------------------------------------------------------
Entrez la station de départ
|: saint_michel.

Entrez la station de destination
|: place_des_arts.

Station intermédiaire ? (nom de la station/non)
|: non.

Entrez l horaire de départ
|: [8, 0].



Récapitulatif ~
La station de départ : saint_michel
La station de destination : place_des_arts
L horaire de départ : [8,0]
Station intermédiaire : non
Départ sur la ligne metro-bleue à 8h3, arrive à 8h7 stations = [saint_michel,d_iberville,fabre,jean_talon]
**Changement**
Départ sur la ligne metro-orange à 8h9, arrive à 8h17 stations = [jean_talon,beaubien,rosemont,laurier,mont_royal,sherbrooke,berri_uqam]
**Changement**
Départ sur la ligne metro-verte à 8h20, arrive à 8h23 stations = [berri_uqam,saint_laurent,place_des_arts]
Bon voyage !


Cherchez un autre itinéraire? 0/non 1/oui
|: 0.


End
true .
```

## Dépendances

Il n'y a pas de dépendances.

## État du projet

Le projet est complété.
