# 🧠 Classification d’images avec CNN – FashionMNIST

Ce projet présente une approche simple et efficace de **classification d’images** avec des **réseaux de neurones convolutifs (CNN)** sur le dataset **FashionMNIST**. Il a été réalisé dans le cadre d’un TP d’initiation au deep learning avec PyTorch.

---

## 📦 Dataset : FashionMNIST

- 70 000 images en niveaux de gris (28×28 pixels)
- 10 classes (T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot)
- Dataset directement accessible via `torchvision.datasets`

---

## 🔧 Objectifs du projet

- Entraîner un modèle CNN pour classifier les images de vêtements
- Comprendre le rôle des couches de convolution et de pooling
- Évaluer les performances du modèle sur un jeu de test

---

## 🚀 Contenu du notebook

- 📥 Chargement et normalisation des données avec `torchvision`
- 🔄 Utilisation de **techniques d’augmentation de données** (flips, rotations, translations…) pour améliorer la robustesse du modèle
- 🧠 Définition d’un modèle **CNN** avec `torch.nn` (convolution, pooling, activation ReLU)
- ❌ Intégration de **Dropout** pour réduire le surapprentissage et améliorer la généralisation
- 🏋️ Entraînement du modèle sur l’ensemble d’apprentissage
- 📊 Évaluation des performances à l’aide de la **précision (accuracy)**


---

## 🛠️ Installation

Assurez-vous d’avoir installé les librairies suivantes :

pip install torch torchvision matplotlib
