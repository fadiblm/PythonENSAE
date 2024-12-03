# PythonENSAE
Python pour la Data Science - 2A
## Fadi B. - Imane Bayoub - Elise Fontaine

## Première version du projet :
Comparaison au niveau macro des opinions publics sur la place de l'impact environnemental du textile dans la consommation des citoyens du pays X VS combien de km est réalisé pour un produits type dans ce pays.

Sélection des pays: panier moyen d'un consommateur par pays

Données:
- Webscrapping pour obtenir les opinions publics: regroupement par nationalité.
- Calcul python pour avoir les émissions liées au km parcourus pour les importations de textiles par pays:
Pour le pays X, on regarde les pays d'où proviennent les importations de textiles. On calcule la distance représentative de chaque pays (km) qu'on multiplie par le facteur d'émission du mode de transport (proxy: avion standard du fret aérien par continent) (base Ademe?). On pondère ensuite par la proportion que représente ce pays dans l'importation totale du textile du pays X: on a les émissions moyenne du textile et le nombre de km.

------------------------------
Sans réelle base de données présente pour notre premier choix de sujet nous nous portons sur un autre sujet. 
L'agriculture biologique en France : nous raconte-t-on des salades ? 
Données présentes sur data.gouv.fr: 
- Parcelles biologiques :https://www.data.gouv.fr/fr/datasets/parcelles-en-agriculture-biologique-ab-declarees-a-la-pac/#/resources
- Achat produits phytosanitaires : https://www.data.gouv.fr/fr/datasets/achats-de-pesticides-par-code-postal/
- Pesticides présent dans les eaux souterraines : https://www.data.gouv.fr/fr/datasets/pesticides-dans-les-eaux-souterraines/
- Professionnels engagés dans le BIO : https://www.data.gouv.fr/fr/datasets/professionnels-engages-en-bio/
Un webscrapping des données sur les réseaux sociaux pour mesurer une éventuelle évolution de la proportion des commentaires sur le BIO et le sentiment qui en découle. 

In fine, avec toutes ses bases de données l'idée est de s'intéresser sur l'Agriculture BIO en France et de voir de potentielle corrélations entre les zones "biologiques" et la consommation effective de pesticide (régression linéaire ?)
Mettre en lumière une éventuelle externalité négative de l'Agriculture BIO et de la polution des eaux : mapping géospatial. 
Avec les sentiments des consommateurs, mettre en lumière une éventuelle prédiction (via ML) de l'augmentation de l'Agriculture BIO en France le tout accompagné de la base de données des professionnels certifiés BIO.
