# Challenge Optimisation 2020

### Structure du projet
---

- `notebooks/` : le notebook principal du challenge regroupant tous les algorithmes essayés.
- `data/` : les instances à résoudre
- `requirements.txt` : librairies utilisées dans le développement

### Algorithmes utilisés
---
- *Algorithme génétique* :  Création d'une population, qui mute avec le temps afin de devenir "meilleure" c'est à dire d'avoir un score plus faible dans ce cas ci.
- *Heuristique naïve* : Initialisation par une séquence aléatoire et amélioration itérative de la séquence.
- *Méthode de Monte-Carlo* : Genération aléatoire de séquences et conservation de la meilleure obtenue.

### Technologies utilisées
---

- Numpy : calcul rapides et efficaces (compilation en C/C++)
- Numba : **JIT** (Just In Time) compilation des fonctions utilisant des boucles notamment, boost la rapidité d'éxécution par 2 au moins.
- Python 3.8.3 : envirronement Anaconda
---

#####  Crédits
*HALLGREN Matthias 09/06/2020 ©*
  