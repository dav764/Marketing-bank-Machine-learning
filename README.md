# Marketing-bank-Machine-learning
Une banque portugaise cherche à promouvoir ses services de dépôts à terme auprès 
de sa clientèle. Pour cela, elle utilise une approche proactive en effectuant des appels 
téléphoniques répétés et espacés pour entrer en contact avec ses clients potentiels. 
L'objectif est d'encourager ces clients à investir dans des dépôts à terme, ce qui peut 
être bénéfique à la fois pour les clients et pour la banque en termes de revenus et de 
fidélisation.
Notre objectif est de développer un modèle prédictif qui peut estimer la probabilité 
qu'un client souscrive à un dépôt à terme en fonction de ses caractéristiques 
démographiques et de son historique de contacts avec la banque. Cela aidera la 
banque à optimiser ses efforts marketing en ciblant les clients les plus susceptibles de 
souscrire, ce qui peut augmenter le taux de conversion et améliorer l'efficacité de la 
campagne.

* Lien de téléchargement de la base de données: [Bank Marketing (kaggle.com)](https://www.kaggle.com/datasets/henriqueyamahata/bank-marketing/data)
[Moro et al., 2014] S. Moro, P. Cortez et P. Rita. A Data-Driven Approach to Predict the 
Success of Bank Telemarketing. Decision Support Systems, sous presse, 
http://dx.doi.org/10.1016/j.dss.2014.03.001

Pour résoudre ce problème, nous avons utilisé le langage python, pour mettre en place 
un système de machine Learning basé sur l’arbre de décision (Decision Tree). 
La méthodologie implique : 
* Importe les données
* Recoder les modalités des variables
* Suppression de trois colonne n’ayant pas de lien avec la prédiction
* Le codage des données ;
* La division en ensembles d'entraînement, de validation et de test ;
* La création et l'entraînement de l’arbre de décision ;
* La prédiction des résultats.
* Visualisation de la courbe du ROC (Receiver Operating Characteristic
