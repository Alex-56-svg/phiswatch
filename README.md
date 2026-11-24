# PhishWatch

Interface de veille phishing et ingénierie sociale.

## Déploiement Cloudflare Workers

Le dossier `public/` contient le site statique. Le Worker configuré est `silent-voice-f482`.

Paramètres Cloudflare Workers Builds :

- branche : `main`
- commande de build : aucune
- commande de déploiement : `npx wrangler deploy`
- configuration : `wrangler.jsonc`
- actifs statiques : `./public`

La revue H1 met à jour `public/app.js` sur GitHub. Un commit accepté par Cloudflare déclenche ensuite le déploiement du Worker.
