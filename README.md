# Exercices data

Une API est une interface permettant de lire, d'ajouter, de modifier et de supprimer de la donnée. Elle se situe entre le client (qui requête) et la base de données (qui stocke l'information).

## Exercice 1

Objectif: reconstruire le modèle d'un produit Etsy sous forme d'un JSON.

A quoi ressemble un JSON? C'est un objet javascript qui prend la forme suivante :

`
var merve = {
  name: 'Merve',
  age: 22,
  is_woman: true
}
`

Recrée Khonshu sous forme d'un objet JSON. Pour t'aider, voici le lien de la fiche produit de [Khonshu](https://www.etsy.com/fr/listing/1204024800/khonshu-poster-a3-marvel-2022-moon) et [voici le modèle fourni par Etsy](https://www.etsy.com/developers/documentation/reference/listing#section_fields).
Dans un premier temps, je te conseille de recréer d'abord le modèle. Ensuite tente de remplir le modèle avec les données de Khonshu.

## Exercice 2

Objectif: créer une base de données sur Airtable et ajouter les 5 derniers posters suivant le modèle.

1. Regarde cette vidéo tutorial de Shubham sur [Airtable](https://www.youtube.com/watch?v=8Hg-UefviE8).
2. Crées un compte sur Airtable et suis la vidéo de Shubham.
3. Maintenant que tu sais à quoi ressemble un objet JSON d'un produit ETSY, recrée un tableau de produits. Chaque colonne correspond à une entrée.
4. Rajoute Khonshu puis les 5 derniers posters.

