# PythonENSAE
Python pour la Data Science - 2A
## Fadi B. - Imane Bayoub - Elise Fontaine

#### REPÉRAGE POUR TROUVER DES DONNÉES ###

##  "https://www.kaggle.com/datasets/purohitgaurav/plastic-based-textiles-in-clothing-industry": grosse bdd tout le nécessaire (consommation d'eau, revenus etc)
##

## Nouvelles idées pour le projet :
Comparaison au niveau macro des opinions publics sur la place de l'impact environnemental du textile dans la consommation des citoyens du pays X VS combien de km est réalisé pour un produits type dans ce pays.

Sélection des pays: panier moyen d'un consommateur par pays

Données:
- Webscrapping pour obtenir les opinions publics: regroupement par nationalité.
- Calcul python pour avoir les émissions liées au km parcourus pour les importations de textiles par pays:
Pour le pays X, on regarde les pays d'où proviennent les importations de textiles. On calcule la distance représentative de chaque pays (km) qu'on multiplie par le facteur d'émission du mode de transport (proxy: avion standard du fret aérien par continent) (base Ademe?). On pondère ensuite par la proportion que représente ce pays dans l'importation totale du textile du pays X: on a les émissions moyenne du textile et le nombre de km.


https://wits.worldbank.org/CountryProfile/en/Country/FRA/Year/2022/TradeFlow/Import/Partner/all/Product/50-63_TextCloth/Show/Partner%20Name;MPRT-TRD-VL;MPRT-PRDCT-SHR;AHS-WGHTD-AVRG;MFN-WGHTD-AVRG;/Sort/MPRT-TRD-VL/Chart/top10# : BDD de la Banque Mondiale sur l'import dans le monde pour le Textile et les Vêtements/// possibilité d'agréger par pays  
