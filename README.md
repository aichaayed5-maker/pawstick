# Site e-commerce

Page d'attente « Projet en construction », posée sur une base prête à accueillir une boutique en ligne.

## Stack

- **Next.js 16** (App Router) : pages rendues côté serveur ou générées à l'avance, pour un bon référencement et des fiches produits rapides. Optimisation des images avec `next/image`, routes API pour recevoir les webhooks de paiement.
- **Cache Components** (activé dans `next.config.ts`) : la structure de chaque page est servie en statique, les parties qui changent (prix, stock, panier) sont chargées à la demande.
- **React 19** et **TypeScript** : typage des produits, paniers et commandes.
- **Tailwind CSS 4** : mise en page rapide et cohérente.
- **ESLint** : vérification du code.

## Démarrer

Prérequis : Node.js 20.9 ou plus récent.

```bash
npm install
npm run dev
```

Puis ouvrir [http://localhost:3000](http://localhost:3000). La page d'accueil se trouve dans `app/page.tsx`.

## Commandes

| Commande | Rôle |
| --- | --- |
| `npm run dev` | Serveur de développement |
| `npm run build` | Build de production |
| `npm run start` | Lance le build de production |
| `npm run lint` | Vérifie le code |
