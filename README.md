# 🛸 PySimverse - Simulation et Contrôle Autonome de Drone

Ce dépôt rassemble mes expérimentations en Python pour le contrôle et la simulation de drones virtuels à l'aide du simulateur **PySimverse**. 

L'objectif de ce projet est de prendre en main le pilotage programmatique, de gérer le contrôle manuel à distance et de réaliser des séquences de missions autonomes dans des environnements 3D simulés (notamment l'environnement du garage).

---

## 🛠️ Technologies Utilisées

* **Python 3.x**
* **PySimverse** (Environnement de simulation et contrôle de drone)

---

## ⚙️ Installation de PySimverse

### 1. Prérequis
Assurez-vous d'avoir **Python 3.8+** et **pip** installés sur votre machine.

### 2. Cloner le dépôt
```bash
git clone [https://github.com/aklrom/pysimverse-drone-control.git](https://github.com/aklrom/pysimverse-drone-control.git)
cd pysimverse-drone-control

```

### 3. Installer la bibliothèque PySimverse

Installez le paquet directement via pip :

```bash
pip install pysimverse

```

*(Optionnel)* Si vous utilisez un environnement virtuel (recommandé) :

```bash
python -m venv venv
# Sur Windows :
venv\Scripts\activate
# Sur Linux/macOS :
source venv/bin/activate

pip install pysimverse

```

---

## 📂 Structure du Dépôt

```text
.
├── RC_control.py          # Contrôle manuel du drone (télécommande / clavier)
├── first_flight.py        # Script d'initiation (décollage, tests de base, atterrissage)
├── Mission1_garage.py     # Première séquence de navigation dans le garage
├── Mission_garage2.py     # Deuxième mission autonome avec trajectoires adaptées
├── Mission3_garage.py     # Mission avancée de franchissement / navigation
└── all_set.py             # Script de vérification et configuration de l'environnement

```

---

## 🎮 Exécution des Scripts

* **Premier vol d'essai :**
```bash
python first_flight.py

```


* **Mode contrôle manuel (RC) :**
```bash
python RC_control.py

```


* **Missions autonomes dans le garage :**
```bash
python Mission1_garage.py
python Mission_garage2.py
python Mission3_garage.py

```



---

## 🎯 Notions et Apprentissages

* Prise en main des commandes de vol basiques (décollage, atterrissage, ajustement de vitesse et d'altitude).
* Navigation programmatique : création de parcours autonomes étape par étape.
* Gestion des commandes de contrôle manuel en temps réel.

```

```
