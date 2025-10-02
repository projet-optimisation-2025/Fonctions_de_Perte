# Étude de la Perte de Huber avec SymPy et Python

## Description
Ce projet illustre la **perte de Huber**, utilisée en régression robuste.  
Il montre :

- Définition et visualisation de la perte de Huber.
- Calcul du gradient et vérification de la convexité avec **SymPy**.
- Exemples sur de petits jeux de données de régression et classification.

## Installation
```bash
git clone <URL_DU_DEPOT>
cd nom_du_projet
pip install -r requirements.txt
requirements.txt doit contenir : numpy, sympy, scikit-learn, matplotlib.

Utilisation
Exécuter huber_analysis.py pour voir les visualisations et calculs symboliques.

Modifier delta dans le code pour changer le seuil de la perte de Huber.

Résultats attendus
Courbe de la perte de Huber.

Gradient symbolique et dérivée seconde.

Graphiques pour les jeux de données de régression et classification.

Licence
Ce projet est libre d’utilisation.
