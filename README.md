# $DIPDOG · He buys every dip

Site du memecoin $DIPDOG : Dip, un teckel qui achète chaque dip. Les bougies rouges sont ses snacks, et plus il hold, plus il s'allonge.
Tout tient dans `index.html`. Double-clique dessus pour l'ouvrir.

Rien sur ce site ne lit le prix ou la market cap. Le graphique du haut est décoratif.

## Contenu
- Hero avec Dip qui cligne des yeux et des répliques qui tournent
- Mini-jouet **Hold to stretch** : maintiens le bouton, Dip s'allonge, rang de "Paper paws" à "Infinite sausage", record sauvegardé, bouton partage X
- Mini-jeu **Dip Catcher** : attrape les bougies rouges (+1) et les os dorés (+5), évite les bougies vertes et les rugs. 3 vies, ça accélère. Flèches / A D / souris ou doigt, P pour pause, record sauvegardé
- Lore, tokenomics, comment acheter, avertissement risques

## Le jour du lancement
Dans `index.html`, bloc `CONFIG` au début du dernier `<script>` :
- `contract` : colle l'adresse pump.fun (CA). Elle s'affiche partout et active les boutons pump.fun et DexScreener.
- `socials` : tes liens X et Telegram.

## Images
- `logo/dipdog-logo-1024.png` : l'image à mettre sur pump.fun et en photo de profil.
- `og-image.png` : l'aperçu quand le lien est partagé. Remplace `SITE_URL` dans `index.html` par l'adresse de ton site.
- `favicon.svg` : l'icône de l'onglet (déjà branchée).
