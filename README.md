# Réseaux Neuronaux (MLP) pour la Sécurisation Decision-LWE

Mini Projet - Module Cryptographie | ENSA Béni Mellal  
Binôme : Machhouri Abderrahman & Zouhiri Hasnae  
Prof : OUNACHAD | S2 - 2025/26

---

## Problématique

Le problème **Decision-LWE** (Learning With Errors) consiste à distinguer entre :
- Des paires **(a, b = a·s + e mod q)** → échantillons LWE valides (label = 1)
- Des paires **(a, u)** où u est uniforme aléatoire (label = 0)

Ce problème est au cœur de la **cryptographie post-quantique** (utilisé dans CRYSTALS-Kyber, sélectionné par le NIST).

---

## Technologies
- Python
- PyTorch
- NumPy / Pandas
- Scikit-learn
- Matplotlib / Seaborn

---


## Installation

```bash
pip install torch pandas numpy scikit-learn matplotlib seaborn
jupyter notebook Decision_LWE_MLP.ipynb
```