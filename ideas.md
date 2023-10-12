# Row level traitment

    select nom_de_table from nom_de_table ;

    select j11, j12 from jdsl_grille_fr_20231011 as j11 full join jdsl_grille_fr_20231012 as j12 on j11 = j12 where j11 is null or j12 is null;

Tester cette technique pour lister les enregistrements d'une table regroupés sur un seul champ
Type du champ obtenuu ?
Applications :
Comparer le contenu de 2 tables tous champs comfondus.
Comparer le contenu de 2 tables tous champs confondus hors clé primaire (jointure avec les tables système)

# Fonction de fenêtrage dans le ORDER BY
A tester. Applications ?

# GROUP BY CASE
A tester. Reprendre le versivore. Efficacité par rapport à d'autes techniques (ex versivore). Pose d'index CASE en conséquence.

# Simuler du procédural avec les CTE, comparatif avec les requêtes imbriquées
Avantages inconvénients - Comparer les plans d'exécution.

# Rubriques :
## Générer et simuler
### Générer au hasard
### Enumérer
## Statistiques
### Dénombrer
Compteer au global, sur filtre, par groupe
### Numéroter
Numéroter au global, ou par groupe, ou uniquement les lignes vérifiant une condition, avec ou sans ex-aequo
### Trier
### Echantilloner
## Mathematiques
## Physique
### Séries temporelles, TimeScale
### FFT
## Chimie
## Biologie
## Algorithmie
### Recuit simulé
### Dijkstra
### Ilôtage
### Voyageur de commerce, CARP
## AI
