# Magtrading – site de démonstration

Site vitrine de démonstration pour Magtrading, quincaillerie à Anderlecht.
Un seul fichier : `index.html` (CSS et JS inclus, aucune dépendance sauf Google Fonts).

## Ouvrir

Double-cliquer sur `index.html`. Tout fonctionne hors ligne (la recherche, la réservation, le FR/NL, le menu).
Sans connexion, seules les polices Google sont remplacées par des polices système.

## Photos

Placer les photos à côté de `index.html` avec ces noms. Tant qu'un fichier manque, un cadre « placeholder » s'affiche à sa place :

- `photo-magasin-1.jpg` (façade, section d'accueil)
- `photo-magasin-2.jpg`, `photo-comptoir.jpg`, `photo-facade.jpg`, `photo-rayon-sanitaire-2.jpg` (galerie)
- `photo-rayon-plomberie.jpg`, `photo-rayon-electricite.jpg`, `photo-rayon-eclairage.jpg`, `photo-rayon-peinture.jpg`,
  `photo-rayon-sanitaire.jpg`, `photo-rayon-outillage.jpg`, `photo-rayon-materiaux.jpg`, `photo-rayon-etancheite.jpg` (cartes « Nos rayons »)

## Logo

`logo-reference.jpg` est la photo du logo imprimé. Le wordmark en en-tête et en pied de page est fait en CSS
pour l'instant ; pour le remplacer, mettre un `<img>` à l'intérieur du bloc `<a class="wordmark">`.

## Données fictives

Prix, stock, avis et numéro de téléphone sont inventés pour la démo et signalés comme tels sur la page.
Les produits de la recherche sont dans le tableau `PRODUCTS` en bas de `index.html`.
