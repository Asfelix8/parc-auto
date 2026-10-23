PARC AUTO — PROTOTYPE MOBILE AVEC IMPORT EXCEL

Contenu : index.html, manifest.webmanifest, sw.js et icônes Android.

Fonctions : gestion locale des véhicules, documents, échéances, interventions et kilométrages; importation Excel (.xlsx); exportation/restauration JSON.

IMPORTANT
- Ce paquet n'est pas encore un APK natif signé.
- Publiez tous les fichiers du dossier sur un hébergement HTTPS.
- Pour importer le classeur Excel, le navigateur doit avoir accès à Internet pour charger la bibliothèque Excel.
- Les données restent sur le navigateur de cet appareil et ne se synchronisent pas entre téléphones.
- Les alertes de ce prototype sont vérifiées lorsque l'application est ouverte; il ne garantit pas de notifications quand elle est fermée.

ÉTAPES SUR ANDROID
1. Extraire le ZIP.
2. Téléverser TOUS les fichiers et dossiers contenus dans parc_auto_mobile vers un hébergement HTTPS (par exemple GitHub Pages).
3. Ouvrir l'adresse HTTPS dans Chrome Android et vérifier que l'application s'affiche.
4. Dans Chrome, menu ⋮ puis « Installer l'application » ou « Ajouter à l'écran d'accueil ».
5. Dans l'application, ouvrir « Sauvegarde » > « Importer le fichier Excel (.xlsx) », puis sélectionner le classeur complété.
6. Vérifier les résultats et exporter une sauvegarde JSON.

POUR UN APK
Après publication HTTPS, ouvrir https://www.pwabuilder.com dans Chrome, entrer l'adresse du site et suivre le parcours Android. La génération peut demander une configuration et une signature. Tester l'installation avant d'utiliser les données en production.
