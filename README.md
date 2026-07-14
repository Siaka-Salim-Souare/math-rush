# Math Rush 🧮⚡

Un jeu de quiz de maths chronométré, aux couleurs de la Guinée — pensé pour les élèves du collège au lycée/terminale, dans l'esprit de la page **Réussir les Maths**.

**Jouer en ligne :** https://siaka-salim-souare.github.io/math-rush/

## Le jeu

- 3 niveaux : **Collège** (calcul mental, fractions, %), **Lycée** (algèbre, géométrie, Pythagore), **Terminale** (dérivées, limites, suites, trigonométrie)
- Questions générées dynamiquement — chaque partie est différente
- Chrono par question, système de vies, combo qui booste le score
- Récap des erreurs en fin de partie pour réviser
- Meilleur score sauvegardé automatiquement par niveau

## Technique

Un seul fichier `index.html` — HTML/CSS/JS pur, aucune dépendance à installer, aucun build. Fonctionne directement dans le navigateur, en local ou hébergé.

## Déploiement (GitHub Pages)

1. Ce repo contient déjà `index.html` à la racine
2. Aller dans **Settings → Pages**
3. Source : branche `main`, dossier `/ (root)`
4. Sauvegarder — le site est en ligne après 1-2 minutes à l'URL ci-dessus

## Mise à jour

Pour ajouter des questions ou changer le design, modifier directement `index.html` — les questions sont générées par des fonctions JavaScript regroupées par niveau (`collegeGenerators`, `lyceeGenerators`, `terminaleGenerators`) en haut du fichier.

## Auteur

Siaka Salim Souaré — [Réussir les Maths](https://www.facebook.com)
