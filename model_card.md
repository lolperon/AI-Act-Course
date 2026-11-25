---
license: mit
language:
- en
datasets:
- iris
metrics:
- accuracy
- f1
pipeline_tag: tabular-classification
---

## Model Details
Model name : Iris Liora
Author : laurent Peron
Date : 25/11/2026
Version : 1.0
Model type : RandomForestClassifier (scikit-learn)
License : MIT

## Intended Use
Intended Use Cases : ce modèle permet d'identifier l'espèce d'un iris, à des fins de recherches scientifiques, pour des docteurs en botanique
3 classes d'iris : Setosa, Versicolor et Virginica
4 caractéristiques par fleur :
longueur du sépale
largeur du sépale
longueur du pétale
largeur du pétale

Out-of-scope Use : ce modèle n'est pas destiné à un usage grand public

## Factors (Facteurs)
Le déséquilibre des classes (Setosa, Versicolor et Virginica)
La distribution des features d'entrée (longueur/largeur des sépales et pétales)

## Metrics (Métriques)
=== Métriques d'évaluation ===
Accuracy : 1.0000

Classification Report :
              precision    recall  f1-score   support

      setosa       1.00      1.00      1.00        10
  versicolor       1.00      1.00      1.00         9
   virginica       1.00      1.00      1.00        11

    accuracy                           1.00        30
   macro avg       1.00      1.00      1.00        30
weighted avg       1.00      1.00      1.00        30


L'accuracy donne une mesure globale des performances du modèle, tandis que la précision, le rappel et le F1-score permettent d'évaluer séparément les performances pour chacune des classes. Les moyennes macro et pondérée complètent l'analyse en vérifiant que les bonnes performances ne sont pas dues à une classe particulière ou à un déséquilibre entre les classes.

## Training Data (Données d'entraînement)
Nom du dataset : Iris flower dataset
Source : sklearn.datasets.load_iris
Taille : 30
Features :  longueur du sépale
            largeur du sépale
            longueur du pétale
            largeur du pétale
Cible : 3 classes d'iris (Setosa, Versicolor et Virginica)

## Evaluation Data (Données d'évaluation)
Source : même dataset que l'entraînement (Iris), split test
Taille : 30
Méthode de séparation : train/test split (précisez le ratio et le random state utilisés dans train.py)
Prétraitements : aucun prétraitement spécifique appliqué

## Quantitative Analyses (Analyses quantitatives)
<!-- Complete after section B.7 -->

## Ethical Considerations (Considérations éthiques)
<!-- Complete after section B.8 -->

## Caveats and Recommendations (Limites et recommandations)
<!-- Complete after section B.9 -->

## Reproductibility
<!-- Complete after section B.10 -->
