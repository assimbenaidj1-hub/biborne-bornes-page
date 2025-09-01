
# Biborne – Page Catégorie : Bornes de commande

Projet Next.js + Tailwind avec une page unique **/ (home)** qui sert d'exemple pour la catégorie **Bornes de commande**.

## Aperçu local
```bash
npm install
npm run dev
# open http://localhost:3000
```

## Déploiement simple (Vercel)
1. Créez un repo GitHub (vide) et poussez ces fichiers.
2. Sur Vercel, **New Project** → Importez le repo → Framework **Next.js** → Deploy.
   - Vercel va installer les dépendances et builder automatiquement.
3. Remplacez les images `public/images/bornes/*.png` par vos visuels produits.

## Notes
- Les composants UI (Button/Badge/Card/Accordion) sont faits maison pour éviter les libs, et stylés avec Tailwind.
- Les JSON‑LD (BreadcrumbList, ItemList, FAQPage) sont inclus pour le SEO.
- Mettez à jour `metadata` dans `app/layout.tsx` si nécessaire (title/meta description).
