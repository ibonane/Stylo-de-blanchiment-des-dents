# Landing Correcteur de Posture — Sénégal

## Mise en ligne GitHub Pages

1. Décompressez le ZIP.
2. Mettez `index.html`, `style.css`, `script.js` et le dossier `assets/` à la racine de votre dépôt GitHub.
3. Activez GitHub Pages depuis les réglages du dépôt.
4. L'URL Apps Script est déjà configurée dans `script.js`.

## Google Sheets / Apps Script

L'endpoint Apps Script configuré est celui fourni pendant la mise en place.

Le script Apps Script doit rester déployé en tant que Web App avec accès public et doit contenir `doPost(e)`.

## Offres

- 1 pièce : 20 900 FCFA
- 2 pièces : 29 900 FCFA
- 3 pièces : 36 900 FCFA

Paiement : à la livraison.
Stock affiché : 33 unités.

## Important

Le frontend utilise `no-cors` pour envoyer le POST à Apps Script. Le navigateur ne peut donc pas lire la réponse JSON d'Apps Script. La page affiche la confirmation après la remise de la requête au navigateur. Le Google Sheet et l'email restent la source de vérité côté marchand.

Le `deliveryFee` est actuellement à 0. Si tu as des frais de livraison, modifie `PRODUCT.deliveryFee` dans `script.js`.
