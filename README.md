# Carnet — notes personnelles

Application statique en HTML/CSS/JavaScript, conçue pour être publiée sur GitHub Pages.

## Publication
1. Crée un dépôt GitHub.
2. Ajoute `index.html`, `manifest.json` et `sw.js` à la racine.
3. Dans Settings → Pages, choisis la branche et le dossier `/ (root)`.
4. Ouvre l'URL HTTPS publiée.
5. Sur iPhone : Safari → Partager → Ajouter à l'écran d'accueil.

## Données et limites
- Les notes sont stockées localement dans le navigateur de cet appareil.
- Exportez régulièrement un fichier JSON depuis « Exporter mes données ».
- L'import remplace les données présentes après confirmation.
- GitHub Pages héberge les fichiers de l'application ; il ne synchronise pas les notes.
- Pour une synchronisation automatique entre appareils, il faudra ajouter un service de stockage/authentification ou utiliser un outil existant.
- La dictée utilise l'API vocale du navigateur si disponible. Sur iPhone, la dictée du clavier iOS reste une alternative.
- Les notes protégées sont chiffrées localement avec AES-GCM et une clé dérivée du mot de passe. Le mot de passe est irrécupérable : conservez-le.
- Ce prototype ne constitue pas une sauvegarde distante ni une solution de chiffrement de bout en bout synchronisée.
