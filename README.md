# TODO-List

NOM PRÉNOM

## Démarrer un serveur HTTP en local

Afin de faciliter le développement, j'ai ajouté en dépendance de développement un utilitaire permettant simplement de démarrer un serveur HTTP pour servir les fichiers du projet.

Pour pouvoir l'utiliser, il faut au préalable l'installer. Pour cela, utiliser la commande `npm install`.

Une fois l'utilitaire installé, il suffit d'utiliser la commande `npm start` pour démarrer le serveur HTTP local.

Par défaut, le serveur est démarré à l'adresse suivante: `http://localhost:5000`. Pour modifier le numéro de port utilisé, si par exemple celui-ci est déjà réservé, utiliser la commande `npm start -- -l <numPort>`.

Plus d'informations sur l'outil `serve` sont disponibles en tapant la commande `npm start -- --help`.
