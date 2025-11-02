# Cours C++ Niveau 3 : Algorithmes et Résolution de Problèmes

Ce dépôt rassemble toutes mes solutions aux exercices et problèmes du **Cours 7 : الخوارزميات (Algorithmes C++ - Niveau 3)**.

L'objectif est de documenter ma compréhension et mon application des algorithmes fondamentaux, des techniques de manipulation de matrices, de la gestion des chaînes de caractères et des opérations sur les fichiers.

---

## 📚 Sujets et Concepts Abordés

Les 51 problèmes de ce cours sont divisés en plusieurs modules principaux :

### 1. Manipulation de Matrices (Problèmes 1-20)
Cette section se concentre sur les opérations fondamentales avec les tableaux bi-dimensionnels (matrices) 3x3.
* [cite_start]**Création et Remplissage** : Remplir une matrice avec des nombres aléatoires [cite: 2] [cite_start]ou des nombres ordonnés[cite: 404].
* [cite_start]**Calculs et Sommes** : Calculer la somme de chaque ligne [cite: 56][cite_start], de chaque colonne [cite: 231][cite_start], ou la somme totale de la matrice[cite: 695].
* [cite_start]**Opérations Matricielles** : Effectuer la transposition d'une matrice [cite: 452] [cite_start]et la multiplication de deux matrices[cite: 536].
* **Analyse et Vérification** :
    * [cite_start]Vérifier si une matrice est une matrice identité [cite: 927][cite_start], scalaire [cite: 994][cite_start], palindrome [cite: 1388] [cite_start]ou creuse (Sparse)[cite: 1121].
    * [cite_start]Comparer des matrices (égalité [cite: 763][cite_start], typicalité [cite: 846]).
* [cite_start]**Recherche de Données** : Trouver le nombre minimum/maximum [cite: 1324][cite_start], compter un nombre spécifique [cite: 1061][cite_start], ou vérifier son existence[cite: 1183].

### 2. Algorithmes (Problèmes 21-22)
* [cite_start]**Série de Fibonacci** : Implémentation à l'aide de boucles [cite: 1440] [cite_start]et de la récursivité[cite: 1465].

### 3. Manipulation de Chaînes de Caractères (Problèmes 23-44)
Cette partie couvre un large éventail de techniques de traitement de texte.
* **Modification de la Casse** :
    * [cite_start]Mettre en majuscule/minuscule la première lettre de chaque mot[cite: 1531, 1567].
    * [cite_start]Convertir toute la chaîne en majuscules/minuscules[cite: 1603].
    * [cite_start]Inverser la casse de chaque caractère[cite: 1680].
* [cite_start]**Comptage** : Compter les lettres majuscules/minuscules [cite: 1722][cite_start], un caractère spécifique (sensible à la casse ou non) [cite: 1799, 1843][cite_start], les voyelles [cite: 1936] [cite_start]et le nombre total de mots[cite: 2070].
* **Découpage et Formatage (Parsing)** :
    * [cite_start]`Split` : Diviser une chaîne en mots dans un vecteur[cite: 2127].
    * [cite_start]`Trim` : Supprimer les espaces au début [cite: 2190][cite_start], à la fin [cite: 2202] [cite_start]ou des deux côtés[cite: 2212].
    * [cite_start]`Join` : Combiner un vecteur [cite: 2232] [cite_start]ou un tableau [cite: 2263] de chaînes en une seule chaîne.
* **Manipulation de Mots** :
    * [cite_start]Inverser l'ordre des mots dans une chaîne[cite: 2289].
    * [cite_start]Remplacer des mots (en utilisant la fonction intégrée `replace` [cite: 2358] [cite_start]ou une approche personnalisée [cite: 2398]).
    * [cite_start]Supprimer tous les signes de ponctuation d'une chaîne[cite: 2500].

### 4. Gestion de Données et Fichiers (Problèmes 45-51)
Cette section applique les concepts précédents pour construire un mini-système de gestion de clients de banque.
* **Conversion de Données** :
    * [cite_start]Convertir un enregistrement (`struct`) client en une ligne de texte (CSV-like)[cite: 2531].
    * [cite_start]Convertir une ligne de texte en enregistrement (`struct`) client[cite: 2590].
* **Opérations CRUD sur Fichiers** :
    * [cite_start]**Create** : Ajouter de nouveaux clients à un fichier (`Clients.txt`)[cite: 2688].
    * [cite_start]**Read** : Afficher tous les clients depuis le fichier [cite: 2775] [cite_start]et trouver un client par son numéro de compte[cite: 2927].
    * [cite_start]**Update** : Mettre à jour les informations d'un client[cite: 3272].
    * [cite_start]**Delete** : Supprimer un client du fichier en se basant sur son numéro de compte[cite: 3070].
