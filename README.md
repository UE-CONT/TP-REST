# UE-AD-A1-REST

Ce TP suit l'architecture suivante:

![Alt text](images\Rest_structure.png?raw=true "Structure des services REST")

## TP vert

Au travers du service User (porte d'accès du réseau de services), un utilisateur peut effectuer différentes opérations:
- get_booking_byuser: Permet de récupérer l'ensemble des bookings d'un utilisateur. Cela fait intervenir les services de Bookings
- get_movies_byuser: Permet de récupérer l'ensemble des movies d'un utilisateur. Cela fait intervenir les services de Movies

Il existe également d'autres méthodes accessible directement pour chaque service (par exemple create_movie dans le service movie). Les différents accès à ces requetes sont décrites dans les différents yaml d'open API.

## Lancement

Pour lancer les services il suffit seulement d'ouvrir 4 terminaux (un pour chaque service) puis à chaque fois de se positionner dans le dossier associé (ex: ``` cd ./movie ```) puis de lancer la commande ``` python service.py ```
