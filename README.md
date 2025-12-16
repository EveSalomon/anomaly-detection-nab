# Détection d’anomalies dans les séries temporelles (NAB)

Ce dépôt contient les notebooks utilisés dans le cadre du projet final portant sur la détection d’anomalies
dans des séries temporelles à l’aide d’autoencodeurs profonds.

## Modèles étudiés
- Autoencodeur LSTM, adapté à la modélisation des dépendances temporelles longues
- Autoencodeur CNN 1D, conçu pour la détection de motifs locaux et de variations rapides

## Jeux de données
- Numenta Anomaly Benchmark (NAB)
  - Séries industrielles (dépendances longues)
  - Séries Twitter (pics locaux)

## Contenu du dépôt
- `notebooks/` : implémentations complètes du prétraitement, de l’entraînement, de la reconstruction et de la détection
- `figures/` : figures utilisées dans le rapport final
- `requirements.txt` : bibliothèques Python nécessaires à la reproduction des expériences (optionnel)

## Reproductibilité
Les expériences présentées dans le rapport sont entièrement reproductibles à partir des notebooks fournis.
Les notebooks permettent de recalculer les erreurs de reconstruction, les seuils de décision et les métriques
de performance (précision, rappel et score F1).

## Remarque
Ce dépôt accompagne le rapport scientifique et a pour objectif de documenter les choix méthodologiques
et expérimentaux réalisés dans le cadre du projet.
