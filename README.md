
# 🎧 RadioPi - Web Radio pour Raspberry Pi


## 📌 Présentation

**RadioPi** est une application de radio web interactive conçue pour Raspberry Pi. Elle propose une interface tactile intuitive qui permet :

- d’écouter des stations locales et internationales,
- de naviguer par **catégorie**, **langue**, **pays** ou **genre**,
- d'ajouter des stations aux **favoris**,
- d'afficher les **logos des stations**, l’**heure**, la **météo**,
- d'enregistrer les radios pour une **écoute hors ligne**,
- de personnaliser le **thème (clair/sombre)** et l'interface (droite/gauche, haut/bas),
- et plus encore !

Ce projet est un PFA visant à intégrer les bibliothèques Python, le matériel embarqué (Raspberry Pi) et des services web dans une application multimédia moderne.

## 🖥️ Interface utilisateur

- Écrite en **Tkinter**
- Compatible **écran tactile**
- Boutons larges et intuitifs
- Supporte le **Bluetooth**, le **casque audio**, le **haut-parleur HDMI**

## 🛠️ Technologies utilisées

- 🐍 Python 3.9+
- 📻 VLC (via `python-vlc`)
- 🖼️ Tkinter (GUI)
- 🌐 RadioBrowser API
- 🔊 ALSA (pour la sortie audio)
- ☁️ API météo (optionnel)

## 🚀 Installation

### 1. Cloner le dépôt
```bash
git clone https://github.com/tonpseudo/RadioPi.git
cd RadioPi
```

### 2. Installer les dépendances
```bash
sudo apt update
sudo apt install vlc python3-tk python3-pip
pip3 install python-vlc requests
```

> Pour activer la sortie audio : assure-toi d’avoir configuré la sortie ALSA ou HDMI correctement.

### 3. Lancer l’application
```bash
python3 radiopi.py
```

## 🧩 Fonctionnalités

- ✅ Lecture/pause/stop
- ✅ Recherche par mot-clé
- ✅ Tri par pays / genre / langue
- ✅ Historique des écoutes
- ✅ Ajout aux favoris
- ✅ Enregistrement des flux
- ✅ Affichage heure/date
- ✅ Changement de thème
- ✅ Interface compacte ou étendue


