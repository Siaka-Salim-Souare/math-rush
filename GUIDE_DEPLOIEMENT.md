# Guide de déploiement — Math Rush sur GitHub Pages

Ce guide t'accompagne pas à pas pour mettre ton jeu **Math Rush** en ligne gratuitement, avec GitHub Pages.

> 💡 **Remarque** : si ton navigateur traduit automatiquement GitHub en français, les noms des boutons/menus changent. Voici les correspondances utilisées dans ce guide :
>
> | Anglais (original) | Français (traduit) |
> |---|---|
> | Settings | Paramètres |
> | Branch | Branche |
> | Save | Enregistrer |
> | Commit changes | Valider les modifications |
> | Upload files | Importer des fichiers |
> | New repository | Nouveau dépôt |

---

## Étape 1 — Créer le dépôt (repo)

1. Connecte-toi sur **github.com** avec ton compte `Siaka-Salim-Souare`
2. Clique sur le bouton **New** (ou le **+** en haut à droite → **New repository**)
3. Donne-lui un nom, par exemple : `math-rush`
4. Laisse-le en **Public**
5. Ne coche aucune case (pas de README, pas de .gitignore) — on va ajouter les fichiers nous-mêmes
6. Clique sur **Create repository**

---

## Étape 2 — Ajouter les fichiers

Sur la page de ton nouveau dépôt vide :

1. Clique sur **uploading an existing file** (ou **Add file → Upload files**)
2. Glisse-dépose les deux fichiers :
   - `index.html`
   - `README.md`
3. En bas de page, écris un petit message, par exemple : `Premier envoi du jeu`
4. Clique sur **Commit changes**

⚠️ Important : le fichier du jeu doit s'appeler exactement **`index.html`** (pas `math_rush.html`), sinon GitHub Pages ne saura pas quelle page afficher en premier.

---

## Étape 3 — Activer GitHub Pages

1. Dans ton dépôt, va dans l'onglet **Paramètres** (Settings, tout à droite de la rangée d'onglets en haut)
2. Dans le menu de gauche, clique sur **Pages**
3. Sous **Build and deployment → Source**, choisis **Deploy from a branch**
4. Sous **Branch**, sélectionne :
   - Branche : `main`
   - Dossier : `/ (root)`
5. Clique sur **Enregistrer** (Save)

---

## Étape 4 — Récupérer le lien

1. Attends 1 à 2 minutes (GitHub construit le site)
2. Recharge la page **Settings → Pages**
3. Un message vert apparaît avec ton lien, du type :

```
https://siaka-salim-souare.github.io/math-rush/
```

4. Clique dessus pour vérifier que le jeu s'ouvre correctement

---

## Étape 5 — Partager

Ton jeu est maintenant accessible à tout le monde via ce lien. Tu peux :

- Le publier sur ta page Facebook **Réussir les Maths**
- L'envoyer directement par message
- L'ajouter dans la bio ou les liens de ta page

---

## Étape 6 — Installer l'app sur ton téléphone (avec le logo)

Le jeu contient maintenant tout ce qu'il faut pour s'installer comme une vraie app, avec son propre logo (tableau noir + racine carrée + éclair jaune, aux couleurs de la Guinée) — pas besoin de passer par le Play Store ou l'App Store.

**Important :** avant d'installer, importe bien ces 5 fichiers dans ton dépôt GitHub (pas seulement `index.html`) :
- `index.html`
- `manifest.json`
- `icon-192.png`
- `icon-512.png`
- `apple-touch-icon.png`

Ils doivent tous être **au même niveau**, à la racine du dépôt.

### Sur Android (Chrome)

1. Ouvre le lien `https://siaka-salim-souare.github.io/math-rush/` dans **Chrome**
2. Appuie sur les **trois points** en haut à droite
3. Choisis **Ajouter à l'écran d'accueil** (ou "Installer l'application" si Chrome le propose directement)
4. Confirme — l'icône du jeu apparaît sur ton écran d'accueil, comme une app normale, avec son propre logo
5. En l'ouvrant depuis cette icône, le jeu se lance en plein écran, sans barre d'adresse du navigateur

### Sur iPhone (Safari)

1. Ouvre le lien dans **Safari** (uniquement Safari, pas Chrome sur iPhone — c'est une limite d'Apple)
2. Appuie sur l'icône **Partager** (le carré avec une flèche vers le haut, en bas de l'écran)
3. Fais défiler et choisis **Sur l'écran d'accueil**
4. Confirme le nom (Math Rush) et appuie sur **Ajouter**
5. L'icône apparaît sur ton écran d'accueil avec le logo

---

## Pour mettre à jour le jeu plus tard

Si tu veux ajouter des questions ou changer quelque chose :

1. Modifie le fichier `index.html` (en local ou directement sur GitHub via le crayon ✏️ à côté du fichier)
2. Envoie les changements (**Commit changes**)
3. Le site se met à jour automatiquement après 1-2 minutes, à la même adresse

---

## En cas de souci

- **La page affiche une erreur 404** : vérifie que le fichier s'appelle bien `index.html` à la racine du dépôt (pas dans un sous-dossier)
- **Le lien ne fonctionne toujours pas après 5 minutes** : retourne dans Settings → Pages et vérifie que la branche/dossier sont bien renseignés, puis clique à nouveau sur Save
- **Tu veux un nom de domaine personnalisé** : possible plus tard via l'option "Custom domain" dans la même page Settings → Pages, si tu achètes un nom de domaine
