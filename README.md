# Décomposition LU en Python

Ce projet illustre la **décomposition LU** d'une matrice carrée, réalisée en Python à l’aide de NumPy et Jupyter Notebook.  
L’objectif est d’approfondir la compréhension des méthodes de factorisation utilisées pour résoudre efficacement les systèmes linéaires.



## Objectif

Implémenter pas à pas la **décomposition LU**

Le notebook détaille :
- Rappel théorique
- L’algorithme de décomposition sans pivot 
- La reconstruction de la matrice $A$ à partir des matrices $L$ et $U$  




## Rappels mathématiques

Pour une matrice carrée $A \in \mathbb{R}^{n \times n}$,  
la **décomposition LU** consiste à écrire :

$$
A = L \times U
$$

où :
- $L$ est une matrice **triangulaire inférieure** (avec des 1 sur la diagonale),
- $U$ est une matrice **triangulaire supérieure**.

Dans certains cas, on introduit aussi une matrice de permutation $P$ pour garantir la stabilité numérique :

$$
P \times A = L \times U
$$

Cette factorisation est très utilisée pour :
- Résoudre des systèmes linéaires $Ax = b$,
- Calculer des inverses de matrices,
- Simplifier les calculs en analyse numérique.



## Technologies utilisées

- **Python 3**
- **NumPy**
- **SciPy** (pour comparaison)
- **Jupyter Notebook**



## Auteur 

**Rayan FRAJ**
