# 🦕 Soroban Dino

Une application mobile pour apprendre le soroban (boulier japonais) avec les dinosaures !

## 🎮 Fonctionnalités

- **10 Mondes progressifs** — de la lecture simple aux calculs avancés
- **60 défis** — Lecture, QCM, Vitesse, Séquences, Calcul
- **15 badges dinosaures** à débloquer
- **Système de streak** quotidien
- **Sons et confettis** à chaque victoire
- **Sauvegarde automatique** (localStorage)
- **100% offline** — aucune connexion requise après chargement

## 🌍 Les 10 Mondes

| Monde | Thème | Contenu |
|-------|-------|---------|
| 🥚 Île des Œufs | Débutant | Nombres 1-9 |
| 🦖 Forêt du T-Rex | Débutant+ | Nombres 10-50 |
| 🦕 Marécage du Stégosaure | Intermédiaire | Nombres 50-99 |
| 🦅 Volcan du Ptéranodon | Intermédiaire+ | Nombres 100-500 |
| 🛡️ Grotte de l'Ankylosaure | Intermédiaire+ | Addition ≤ 20 |
| 🌊 Lac des Diplodocus | Avancé | Soustraction |
| 🌿 Prairie du Brachiosaure | Avancé | Grands nombres 500-9999 |
| ⚡ Montagne du Vélociraptor | Avancé+ | Addition & Soustraction ≤ 100 |
| 🏛️ Cité des Tricératops | Expert | Multiplication ×2,3,5,10 |
| 🌋 Temple du Grand Maître | Maître | Défis ultimes |

## 🚀 Déploiement sur GitHub Pages

### Méthode simple (sans terminal)

1. Crée un compte sur [github.com](https://github.com)
2. Clique sur **"New repository"**
3. Nomme le repo : `soroban-dino`
4. Coche **"Public"**
5. Clique **"Create repository"**
6. Clique **"uploading an existing file"**
7. Glisse-dépose les fichiers `index.html` et `README.md`
8. Clique **"Commit changes"**
9. Va dans **Settings → Pages**
10. Source : **"Deploy from a branch"** → branche `main` → dossier `/ (root)`
11. Clique **Save**
12. Ton app est en ligne : `https://[ton-pseudo].github.io/soroban-dino`

### Méthode terminal (Mac)

```bash
cd ~/Downloads/soroban-dino
git init
git add .
git commit -m "🦕 Soroban Dino - première version"
git branch -M main
git remote add origin https://github.com/[TON-PSEUDO]/soroban-dino.git
git push -u origin main
```

Puis active GitHub Pages dans Settings → Pages.

## 📱 Utilisation

L'app est optimisée mobile. Ajoute-la à l'écran d'accueil du téléphone :
- **iPhone** : Safari → bouton Partager → "Sur l'écran d'accueil"
- **Android** : Chrome → menu ⋮ → "Ajouter à l'écran d'accueil"

## 🎯 Progression recommandée (3 semaines)

**Semaine 1** — 10-15 min/jour
- Monde 1 : Île des Œufs (jours 1-2)
- Monde 2 : Forêt du T-Rex (jours 3-4)
- Monde 3 : Marécage du Stégosaure (jours 5-7)

**Semaine 2** — 15 min/jour
- Monde 4 : Volcan du Ptéranodon (jours 8-9)
- Monde 5 : Grotte de l'Ankylosaure (jours 10-11)
- Monde 6 : Lac des Diplodocus (jours 12-14)

**Semaine 3** — 15-20 min/jour
- Monde 7 : Prairie du Brachiosaure (jours 15-16)
- Monde 8 : Montagne du Vélociraptor (jours 17-18)
- Monde 9 : Cité des Tricératops (jours 19-20)
- Monde 10 : Temple du Grand Maître (jours 21)

## 🛠️ Technique

- HTML/CSS/JavaScript pur — aucune dépendance externe
- Sauvegarde : `localStorage` (données sur l'appareil)
- Compatible : Chrome, Safari, Firefox, Edge
- Responsive : mobile et desktop
