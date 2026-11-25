# Projet SIEVE — Classification de logs

## Description
Projet de classification automatique de journaux système (*logs*) à partir du dataset SIEVE (`output_0`).

Le projet comprend :
- La comparaison de 8 modèles de Deep Learning.
- L'évaluation de la robustesse du modèle Peephole LSTM avec la Data Augmentation et l'entraînement adversarial (FGSM).
- L'évaluation en environnement Open World pour détecter les classes inconnues.

## Modèles étudiés
- Simple RNN
- GRU
- Peephole LSTM
- Tiny LSTM
- GPT-1
- DistilGPT2
- DistilBERT
- TinyBERT

## Environnement
- Python
- PyTorch
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Exécution
1. Installer les dépendances :

```bash
pip install -r requirements.txt
```

2. Placer les fichiers du dataset dans le dossier `processed_data/`.

3. Ouvrir les notebook Jupyter.

4. Exécuter les cellules dans l'ordre.

## Résultats
Les résultats des expérimentations comprennent les métriques de classification, les mesures de robustesse, les taux de rejet des classes inconnues et les temps d'entraînement.

## Dataset
Variante utilisée : `output_0`  
Nombre de classes : 30
