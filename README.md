# OC_PROJET9
Réalisez un traitement dans un environnement Big Data sur le Cloud

## Objectifs :
- Mettre en place une infrastructure Big Data scalable sur AWS EMR pour traiter efficacement de grands volumes d'images de fruits.
- Améliorer le script PySpark existant en intégrant des fonctionnalités essentielles pour l'inférence de modèles :
- Diffusion des poids du modèle TensorFlow sur les nœuds du cluster pour une inférence distribuée.
- Réduction de dimensionnalité à l'aide de PCA pour optimiser les performances et la qualité des résultats.
- Assurer la conformité RGPD en configurant l'environnement AWS pour utiliser des serveurs situés en Europe.
- Évaluer la pertinence et l'efficacité de l'architecture EMR pour les besoins futurs de la start-up, en particulier en termes de coût et de performance.

## Contexte :
Vous travaillez au sein de la start-up "Fruits!" qui développe une application mobile permettant d'identifier des fruits à partir d'une photo. Votre mission consiste à améliorer une première version d'une pipeline de traitement d'images basée sur AWS EMR et PySpark, réalisée par un précédent collaborateur. L'objectif est de préparer cette infrastructure à gérer des volumes de données croissants et à supporter l'inférence de modèles de classification d'images plus complexes.

Missions :
- Prendre en main le script PySpark existant et analyser son fonctionnement.
- Implémenter la diffusion des poids du modèle TensorFlow sur les nœuds du cluster en suivant les recommandations de l'article "Distributed model inference using TensorFlow Keras".
- Intégrer une étape de réduction de dimensionnalité PCA dans le pipeline pour améliorer les performances et la qualité des résultats.
- Configurer l'environnement AWS EMR pour garantir la conformité RGPD et utiliser des serveurs situés en Europe.
- Rédiger une documentation détaillée expliquant les différentes étapes du pipeline et les choix techniques effectués.
- Réaliser une démonstration de l'infrastructure EMR opérationnelle et du script PySpark amélioré.
- Évaluer les coûts associés à l'utilisation d'EMR et proposer des optimisations si nécessaire.
- Formuler des recommandations sur la pertinence de généraliser cette solution pour les projets futurs de la start-up.
