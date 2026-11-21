# AFRO FOREVER – Musée digital et marketplace UNIFAC 2026

Site one-page statique (HTML/CSS/JS, aucune dépendance). Tout le contenu se modifie dans l'objet `window.SITE`, en haut du dernier `<script>` de `index.html`.

## Déploiement
1. Créer un dépôt GitHub et pousser ce dossier (`git init && git add . && git commit -m "AFRO FOREVER" && git push`).
2. Sur Vercel : *Add New → Project*, importer le dépôt, laisser les réglages par défaut (Framework : Other, pas de build), puis *Deploy*.

## QR codes
- Les liens directs ont la forme `https://votre-site.vercel.app/#stand-ID` (ex. `#stand-portrait-bleu`).
- Sur le site en ligne, ouvrir une fiche d'œuvre → « Afficher le QR code » : l'adresse de base est celle du site déployé.
- « Outils organisateur » (pied de page) imprime tous les QR codes d'un coup.
- Si vous changez de domaine, régénérez les QR codes.

## À compléter
- Logos : placer les fichiers dans `images/` et renseigner `src` dans `logos` et `sponsors`.
- Vidéos : à ajouter (`video.youtubeId` pour YouTube).
- Contact et réseaux sociaux : `contact.email`, `contact.phone`, `contact.social` (vides = masqués).
- Formulaire : renseigner `formEndpoint` (ex. Formspree), sinon il reste en mode démonstration.
- Œuvres : remplacer titres et artistes provisoires dans `stands`.
