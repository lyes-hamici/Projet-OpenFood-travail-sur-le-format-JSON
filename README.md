Le site https://world.openfoodfacts.org/, propose des données sur des produits alimentaires.

Ce site est alimenté par des consommateurs bénévoles

On peut avoir accès aux données (json) d'un produit si on connaît son code barre : regardons le produit de code 3270160860166.
Essayez cette URL : https://fr.openfoodfacts.org/api/v0/produit/3270160860166.json.

Comme vous pouvez le constater il y a énormément de données. Il y a un filtre dans la barre en haut de la fenêtre qui vous permet de rechercher des paramètres particulier. Tout est en anglais. Taper par exemple "sugar". Il y a plusieurs résultats, mais on trouve assez rapidement le paramètre `sugars_100g` qui correspond à la quantité de sucre pour 100g. Il se trouve dans `product` puis dans `nutriments`.
Le programme suivant affiche le taux de sucre et l'étiquette du produit.
