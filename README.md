# Projet_Chien_Chocolat

## Objectif

Ce dépôt contient des notebooks qui simulent et analysent la dynamique de la théobromine chez le chien après ingestion de chocolat.

## Fichiers du projet

- **`Modèle.ipynb`** : Simulation du modèle mathématique. Contient la définition des équations différentielles, les conditions initiales et les simulations de scénarios (variations de poids, quantité et type de chocolat).

- **`Sensibilité_Robustesse.ipynb`** : Analyse de sensibilité et robustesse du modèle. Évalue l'impact de la variation des paramètres clés sur les observables (Dmax, Smax, temps de récupération).

## Prérequis

- Python 3.10 ou plus récent
- Un gestionnaire de paquets Python (`pip` ou équivalent)
- Jupyter Notebook ou VS Code avec support notebooks

## Installation des dépendances

Ouvrir un terminal dans le dossier du projet puis exécute :

```powershell
python -m pip install --upgrade pip
python -m pip install numpy scipy matplotlib jupyter
```

## Exécution des notebooks

### Modèle.ipynb

Option 1 : avec Jupyter Notebook

```powershell
cd "c:\Users\Capucine\OneDrive\Desktop\BTBI\3 BTBI\S2\PhysioMaths\Projet\Projet_Chien_Chocolat"
python -m notebook Modèle.ipynb
```

Option 2 : avec VS Code

1. Ouvrir le dossier `Projet_Chien_Chocolat` dans VS Code.
2. Ouvrir `Modèle.ipynb`.
3. Choisir un interpréteur Python avec les paquets installés.
4. Exécuter les cellules du notebook.

### Sensibilité_Robustesse.ipynb

Même procédure que pour `Modèle.ipynb`, en remplaçant le nom du fichier.

## Notes

- `Modèle.ipynb` contient la définition du modèle, les simulations et les figures correspondantes.
- `Sensibilité_Robustesse.ipynb` analyse comment les résultats changent selon les paramètres du modèle.

