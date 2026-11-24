# PhishWatch

Interface de veille phishing et ingénierie sociale.

## Déploiement Cloudflare Workers

Le dossier `public/` contient le site statique. Connecter ce dépôt à Cloudflare Workers Builds avec :

- branche : `main`
- commande de build : aucune
- commande de déploiement : `npx wrangler deploy`
- fichier de configuration : `wrangler.jsonc`

Remplacer `NOM_EXACT_DE_TON_WORKER` dans `wrangler.jsonc` par le nom exact du Worker Cloudflare.
