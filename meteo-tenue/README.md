# Météo & Tenue

Petite application météo, conçue pour téléphone et ordinateur. Elle affiche les prévisions des 7 prochains jours en degrés Celsius, avec des icônes météo et un conseil vestimentaire et de parfums quotidien.

## Utilisation rapide

1. Décompresse `meteo-tenue.zip`.
2. Ouvre `index.html` dans Chrome ou un autre navigateur récent.
3. Recherche ta ville. L'application démarre avec Alger par défaut.

La météo et la recherche de ville nécessitent une connexion Internet. La recherche manuelle fonctionne sans clé API. Selon le navigateur, la géolocalisation peut demander que le site soit publié en HTTPS (un fichier ouvert directement depuis le téléphone ne permet pas toujours l'accès GPS).

## Installer sur l'écran d'accueil avec GPS

1. Ouvre l'adresse HTTPS générée dans Chrome sur ton téléphone.
2. Menu ⋮ de Chrome → **Ajouter à l'écran d'accueil** ou **Installer l'application**.

## API utilisée

- Prévisions sur 7 jours : Open-Meteo Forecast API.
- Recherche de ville : Open-Meteo Geocoding API.
- Aucune clé API requise pour un usage non commercial courant.

Le bloc parfum propose plusieurs parfums pour aujourd’hui seulement : touche « Autre suggestion » pour passer au suivant. La liste est recalculée quand les prévisions du jour changent.

Le bouton « Installer » peut apparaître automatiquement sur les navigateurs compatibles. Sinon, depuis Chrome sur Android, ouvre le site publié en HTTPS, touche le menu ⋮ puis « Ajouter à l’écran d’accueil » ou « Installer l’application ». Ouvrir simplement le fichier HTML depuis les téléchargements ne permet pas une installation PWA complète 

Les recommandations de vêtements sont des règles indicatives fondées sur les températures minimales/maximales et le vent ; elles ne remplacent pas ton appréciation des conditions locales.


Voila Voila ca devrait etre tous
