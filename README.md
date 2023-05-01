# logistique

L'objectif de ce projet était de créer un modèle de classification capable de prédire la présence d'une maladie cardiaque chez un patient en fonction de ses caractéristiques physiques telles que son âge, son sexe, son taux de cholestérol, etc.

Les données utilisées pour entraîner et tester le modèle ont été obtenues à partir d'un test physique effectué sur les patients, incluant des échantillons de sang et un test d'exercice physique. La présence de maladie cardiaque est déterminée par le champ "target", qui prend la valeur 1 si la maladie est présente et 0 sinon.

Après avoir importé les bibliothèques nécessaires, nous avons importé les données à partir d'un fichier csv disponible sur GitHub. Nous avons ensuite effectué une analyse exploratoire des données et visualisé les résultats à l'aide de bibliothèques telles que Seaborn et Matplotlib. Les résultats ont montré qu'il y avait une corrélation entre certains des attributs physiques et la présence de maladie cardiaque.

Nous avons ensuite créé un modèle de régression logistique en utilisant la bibliothèque Scikit-Learn. Le modèle a été entraîné sur un ensemble de données d'entraînement et testé sur un ensemble de données de test distinct. Les performances du modèle ont été évaluées à l'aide de métriques telles que la précision et le rappel.

En conclusion, nous avons réussi à créer un modèle de classification capable de prédire avec précision la présence d'une maladie cardiaque chez un patient en utilisant ses caractéristiques physiques. 
