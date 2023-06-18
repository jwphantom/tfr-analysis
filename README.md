# tfr-analysis
Analyse de la fécondité et des facteurs démographiques associés

Ce script en Python effectue une analyse multivariée sur un ensemble de données appelé "United Nations Social Indicators Data". Les données sont extraites d'un fichier texte appelé "UnitedNations.txt" et comprennent plusieurs variables relatives aux indicateurs sociaux des différents pays.

## Fichier de données

- Nom du fichier: UnitedNations.txt
- Source: Téléchargé à partir du site http://www.un.org/Depts/unsd/social/main.htm en 1968.

## Variables

Les variables incluses dans le jeu de données sont les suivantes:

1. **region**: Région géographique du pays (Afrique, Amérique, Asie, Europe, Océanie).
2. **tfr**: Taux de fécondité total, nombre moyen d'enfants par femme.
3. **contraception**: Pourcentage de femmes mariées utilisant une méthode de contraception.
4. **educationMale**: Nombre moyen d'années de scolarité pour les hommes.
5. **educationFemale**: Nombre moyen d'années de scolarité pour les femmes.
6. **lifeMale**: Espérance de vie à la naissance pour les hommes.
7. **lifeFemale**: Espérance de vie à la naissance pour les femmes.
8. **infantMortality**: Nombre de décès d'enfants de moins d'un an pour 1000 naissances vivantes.
9. **GDPperCapita**: Produit intérieur brut par habitant en dollars américains.
10. **economicActivityMale**: Pourcentage d'hommes économiquement actifs.
11. **economicActivityFemale**: Pourcentage de femmes économiquement actives.
12. **illiteracyMale**: Pourcentage d'hommes de 15 ans et plus analphabètes.
13. **illiteracyFemale**: Pourcentage de femmes de 15 ans et plus analphabètes.

## Instructions d'utilisation

1. Téléchargez le fichier de données "UnitedNations.txt" à partir du lien fourni dans le script.
2. Exécutez le script dans un environnement Python compatible (par exemple, Jupyter Notebook).
3. Les résultats de l'analyse descriptive et multivariée seront affichés à l'écran.

Note: Si certaines valeurs sont manquantes, le script utilise une imputation par la moyenne pour les remplacer.

N'hésitez pas à explorer le code pour obtenir des informations plus détaillées sur l'analyse réalisée.

## Remarques

- Dans quelques cas où les pourcentages d'hommes et de femmes analphabètes de 15 ans et plus étaient indisponibles, ces variables ont été complétées par une imputation de régression à partir des pourcentages correspondants des personnes de 25 ans et plus qui sont analphabètes.
- Les données manquantes sont indiquées par NA.

**Note**: Ce fichier README a été généré automatiquement par le modèle de langage GPT-3.5 de OpenAI en se basant sur les informations disponibles. Veuillez le vérifier et l'ajuster selon vos besoins spécifiques.
