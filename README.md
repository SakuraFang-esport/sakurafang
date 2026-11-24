# SAKURAFANG — site vitrine

Site statique prêt à être publié sur **GitHub Pages**. Le site utilise le logo fourni dans `assets/logo.png`.

## Publier sur GitHub Pages

1. Créez un dépôt GitHub, par exemple `sakurafang`.
2. Décompressez l'archive et ajoutez **tous les fichiers** à la racine du dépôt (`index.html`, `styles.css`, `script.js`, `assets/`).
3. Dans le dépôt, ouvrez **Settings → Pages**.
4. Dans **Build and deployment**, choisissez **Deploy from a branch**.
5. Sélectionnez la branche `main` et le dossier `/ (root)`, puis cliquez sur **Save**.
6. GitHub affichera l'adresse publique du site dans cette même page après le déploiement.

## Personnalisation

- Les textes et les liens se trouvent dans `index.html`.
- Les couleurs, tailles et mises en page se trouvent dans `styles.css`.
- Les interactions du menu et de navigation se trouvent dans `script.js`.
- Remplacez `assets/logo.png` pour changer le logo, en conservant le même nom de fichier.

## À propos des alertes de live Discord

GitHub Pages ne fait qu'héberger des fichiers statiques : il ne peut pas surveiller une chaîne de streaming ni envoyer un ping Discord de lui-même. La section Live est donc prête côté présentation, mais l'automatisation doit être raccordée séparément.

Pour la mettre en service, il faudra connaître la plateforme de diffusion (Twitch, YouTube, etc.) et le compte/chaîne à surveiller. Une solution possible est un petit bot ou une automatisation hébergée séparément, avec les identifiants conservés en secrets (jamais dans le code public du site), qui détecte le début du live puis publie une annonce dans le salon Discord choisi. Le webhook Discord ou le bot devra avoir les permissions adaptées.

## À savoir

- Les liens YouTube, TikTok et Discord fournis ont été intégrés.
- Les candidatures de chaque pôle renvoient vers le Discord.
- Les catégories demandées sont visibles sur la page : Valorant (Premier / Console), Rocket League (Champion / Grand Champion), Overwatch (Équipe Overwatch), et recrutement (Valorant PC / Console, Rocket League, Overwatch, Staff).
- La police Google Fonts nécessite une connexion Internet ; des polices système prennent le relais si elle n'est pas disponible.
