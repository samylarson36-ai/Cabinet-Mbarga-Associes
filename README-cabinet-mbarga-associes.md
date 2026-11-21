# Cabinet Mbarga & Associés

Projet d’entraînement : site vitrine d’un cabinet d’avocats fictif à Akwa, Douala. Le nom, les adresses, les téléphones, les tarifs et les personnes sont **fictifs** et ne correspondent à aucune entreprise réelle.

## Pages

- `index.html` : Accueil : domaines d’intervention, équipe, méthode, FAQ et prise de rendez-vous
- `equipe.html` : Présentation détaillée des trois avocats
- `actualites.html` : Articles juridiques fictifs, dépliables au clic

## Fonctionnalités

- Six domaines d’intervention (affaires, famille, pénal, foncier, travail, arbitrage)
- FAQ dépliable et méthode de travail en quatre étapes
- Formulaire de demande de rendez-vous (`mailto:`)
- Illustrations vectorielles (SVG) des avocats
- Design responsive (mobile, tablette, ordinateur) avec menu burger
- Aucune dépendance : HTML, CSS et JavaScript natifs, polices Google Fonts

## Structure

```
cabinet-mbarga-associes/
├── index.html
├── css/style.css
├── js/main.js
├── img/            illustrations SVG
├── favicon.svg
└── README.md
```

## Lancer en local

Ouvre `index.html` dans un navigateur. Pour un test plus proche de la production :

```
python3 -m http.server 8000
```

puis rends-toi sur `http://localhost:8000`.

## Déployer

- **Vercel** : importe le dépôt, aucun réglage de build (site statique).
- **GitHub Pages** : Settings → Pages → branche `main`, dossier `/ (root)`.

## Personnaliser

- Remplace l’adresse `.example` des formulaires par ton e-mail : attribut `data-mail` dans `index.html`.
- Les couleurs sont des variables au début de `css/style.css` : `--ac` (laiton) et `--hd` (vert sombre de l’en-tête).
- Remplace les fichiers de `img/` par de vraies photos en gardant les mêmes noms (adapte l’extension dans les balises `<img>` si besoin).
