# Ford Companion

Application web installable (PWA) pour iPhone, immédiatement utilisable sans adaptateur OBD.

## Déploiement GitHub + Cloudflare Pages
1. Créez un dépôt GitHub vide.
2. Déposez **le contenu de ce dossier à la racine** du dépôt.
3. Dans Cloudflare Pages, connectez le dépôt.
4. Framework preset : `None` ; commande de build : vide ; dossier de sortie : `/`.
5. Une fois le site ouvert dans Safari sur l’iPhone : **Partager → Sur l’écran d’accueil**.

## Fonctions
- Interface sombre inspirée de Ford et de CarPlay.
- Lancement rapide de LBC, Apple Music, Podcasts, Spotify et YouTube Music.
- Navigation Apple Plans, Google Maps ou Waze.
- Trajet GPS : vitesse, distance, durée, vitesse moyenne, altitude.
- Historique carburant, entretien, pneus et Road Trips importés depuis le fichier fourni.
- Fonctionnement hors ligne après la première ouverture.

## Important
Une PWA ne peut pas afficher ou contrôler directement les applications audio dans sa propre interface. Les boutons ouvrent donc les applications correspondantes. Le son est ensuite transmis à SYNC par Bluetooth.
