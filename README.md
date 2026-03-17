# Simon Game 🎮

Un petit jeu Simon classique développé en **HTML, CSS et JavaScript**.  
Le but du jeu est de mémoriser et reproduire une séquence de couleurs qui devient de plus en plus longue à chaque niveau.

🔗 **Live Demo** : https://marwenkhlifi15.github.io/simon-game/

---

## 🎯 Objectifs du projet

- Pratiquer la **manipulation du DOM** avec JavaScript.
- Gérer les **événements clavier et clic**.
- Travailler avec des **tableaux**, des **séquences aléatoires** et la logique de jeu.
- Ajouter des **effets sonores** et des animations simples pour améliorer l’expérience utilisateur.

---

## 🧩 Règles du jeu

1. Appuie sur **n'importe quelle touche** du clavier pour démarrer la partie.
2. Le jeu affiche une séquence de couleurs (une au début, puis de plus en plus longue).
3. Clique sur les boutons de couleur dans **le même ordre** que la séquence affichée.
4. Si tu te trompes :
   - Un son d’erreur est joué.
   - L’écran clignote en rouge.
   - Le message « *Game Over, Press Any Key to Restart* » s’affiche.
5. Appuie sur une touche pour **recommencer** depuis le niveau 1.

---

## 🛠️ Technologies utilisées

- **HTML5** – structure de la page
- **CSS3** – styles et mise en forme
- **JavaScript (ES6)** – logique du jeu
- **jQuery** – gestion des événements et sélecteurs plus simples
- **Audio** – sons pour chaque bouton + son d’erreur

---

## 📂 Structure du projet

```text
.
├── index.html       # Structure principale du jeu
├── styles.css       # Styles du jeu (layout, couleurs, animations)
├── game.js          # Logique du jeu (séquence, input utilisateur, vérification)
└── sounds/          # Sons pour chaque couleur + son d'erreur
    ├── red.mp3
    ├── blue.mp3
    ├── green.mp3
    ├── yellow.mp3
    └── wrong.mp3
