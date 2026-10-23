# Ma Caisse Stickers — version 4

Dépose les fichiers à la racine du dépôt GitHub Pages en remplaçant les fichiers de l'ancienne version.

## Fonctions
- Catalogue avec photos, références manuelles, catégories et emplacement (panneau / présentoir).
- Stock minimum personnalisé par sticker et alertes de stock.
- Panier, encaissement, monnaie à rendre et historique des ventes.
- Onglet « Ma caisse » : date de la journée, ouverture avec fond de caisse et seuil minimum à conserver, bilan des ventes, caisse théorique, saisie du comptage réel, calcul de l'écart et clôture.
- Historique des journées et possibilité de rouvrir une journée clôturée pour corriger une erreur.
- Export/import JSON incluant produits, ventes, journées et photos.
- Fonctionnement hors ligne via service worker.

## Important avant mise à jour
1. Ouvre l'ancienne application et exporte une sauvegarde JSON si elle est accessible.
2. Garde cette sauvegarde dans l'app Fichiers.
3. Remplace les fichiers du dépôt GitHub par ceux de cette archive, sans changer l'adresse du site si possible.
4. Une fois la nouvelle version chargée, importe la sauvegarde si les données n'apparaissent pas automatiquement.

Les données restent stockées localement sur chaque appareil. La synchronisation automatique entre iPhone et tablette n'est pas activée.

## Règles de caisse
- Total des ventes : somme des ventes de la journée.
- Caisse théorique : fond de caisse de départ + total des ventes.
- Écart : montant réellement compté - caisse théorique.
- Le fond de caisse est affiché séparément et n'est pas considéré comme un gain.


## Version 6 — ajout rapide des stickers
- Le champ panneau / présentoir propose les emplacements déjà utilisés dans une liste déroulante (flèche), tout en permettant d’en saisir un nouveau.
- Le dernier panneau utilisé est mémorisé et prérempli pour le prochain sticker.
- Le stock et le stock minimum sont initialisés à 1 lors de l’ajout d’un nouveau sticker.


## Version 7 — catégories rapides
- Suggestions de catégories prêtes à l’emploi : Chats, Chiens, Loups, Oiseaux, Chevaux, Animaux, Fleurs, Fantaisie, Humour, Jeux vidéo, Nourriture et Autres.
- Les catégories personnalisées déjà utilisées sont automatiquement proposées dans la liste.
- La dernière catégorie choisie est mémorisée et préremplie pour le sticker suivant ; elle reste modifiable.


## Version 8 — catégories et panneaux personnalisés
- Les catégories sont créées par l'utilisatrice en les saisissant; elles sont ensuite mémorisées dans la liste déroulante.
- Les panneaux / présentoirs sont également mémorisés, sans liste de noms imposée.
- Le dernier panneau et la dernière catégorie utilisés restent présélectionnés pour accélérer les ajouts.
- Les listes personnalisées sont incluses dans les exports de sauvegarde et restaurées lors d'un import.
