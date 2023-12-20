# Rice Cooker Simulator

Le code a été refactorisé pour améliorer sa lisibilité, sa concision et sa maintenabilité.

[Lien vers le projet source](https://github.com/hei-school/cc-d4-rice-cooker-ci-NyAndoMayah/blob/feat/js/js/main.js)

## Modification ajoutée

1. **Utilisation d'une Classe `RiceCooker` :**  
   La classe `RiceCooker` regroupe les différentes fonctionnalités du rice cooker. Cela améliore la structure du code en rendant chaque fonctionnalité plus modulaire.

2. **Méthode `resetCooker` pour la réinitialisation des états :**  
   Une nouvelle méthode `resetCooker` a été créée pour réinitialiser les états du Rice cooker. Cela remplace la logique de réinitialisation précédemment présente dans la fonction `removeRice`, rendant le code plus clair.

3. **Simplification de la logique avec une boucle `while (true)`:**  
   Cela améliore la compréhension du flux de contrôle et rend le code plus élégant.

4. **Suppression de la variable inutile `condition`:**  
   La variable `condition` a été supprimée, simplifiant davantage le code en utilisant directement la boucle `while (true)`.

5. **Remplacement de la structure `if...else if...else` par une structure `switch`:**  
   La fonction `simulateRiceCooker` utilise désormais une structure `switch` pour gérer les différentes options. Cela rend le code plus lisible et évite l'imbriquement excessif de structures `if...else if...else`. La structure `switch` est choisie pour sa concision, sa lisibilité et son efficacité.

## Complexité du Code Avant et Après Refactor

Avant la refactorisation, le code avait une logique conditionnelle imbriquée, ce qui rendait la compréhension et la maintenance plus difficiles. Après la refactorisation, le code est plus modulaire, utilise une logique simplifiée, et bénéficie d'une meilleure lisibilité grâce à l'utilisation de la classe `RiceCooker` et de la structure `switch`.