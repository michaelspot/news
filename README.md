## 📰 Widget « BOSS, VOICI LES NEWS » pour iPhone

Ce script crée un widget iOS 14+ affichant les 6 dernières actualités (texte uniquement) de deux flux RSS (possibilité d'en ajouter plus si besoin), avec un titre sur deux lignes et des séparateurs gris.

---

### 📋 Prérequis

* iPhone sous iOS 14 ou supérieur
* [Scriptable](https://scriptable.app/) installé depuis l’App Store
* Connaissances de base sur l’ajout de widgets iOS

---

### 🚀 Installation

1. Ouvrez l’app **Scriptable** sur votre iPhone.

2. Dans l’onglet **Scripts**, appuyez sur le bouton **+** en haut à droite.

3. Donnez un nom au script, par exemple `NEWS`.

4. Collez l’intégralité du code du "main-file" dans l’éditeur

5. Appuyez sur **Done** pour enregistrer.

---

### ⚙️ Configuration du widget

1. Revenez sur l’écran d’accueil de votre iPhone.
2. Touchez et maintenez un espace vide pour entrer en mode **Jiggle**.
3. Appuyez sur le **+** en haut à gauche.
4. Sélectionnez **Scriptable** dans la liste.
5. Choisissez la taille de widget souhaitée (le widget est prévu pour medium).
6. Appuyez sur **Add Widget**, puis **Done**.
7. Touchez le widget pour sélectionner le script **NEWS**.

---

### 🔧 Personnalisation

* **Flux RSS** : modifiez le tableau `FEEDS` au début du code.
* **Nombre d’articles** : changez `max` pour chaque URL (mais influence directement la visiblilité après)
* **Intervalle de rafraîchissement** : ajustez `refreshAfterDate`.

---

Open-source servez-vous modifiez
