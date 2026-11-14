# Ecodan Pilotage

Interface web personnelle pour une installation Mitsubishi Ecodan.

## Périmètre matériel
- Unité extérieure : PUHZ-SHW112VAA
- Module hydraulique : EHSC-VM6C
- Régulation : FTC5
- Interface Wi-Fi : MAC-587IF-E
- Thermostat radio : PAR-WT50R-E
- Récepteur radio : PAR-WR51R-E
- Chauffage seul, une zone, sans ECS

## État du projet
Prototype PWA front-end. Les valeurs sont volontairement laissées vides : aucune connexion réelle à MELCloud n'est encore configurée.

## Sécurité
- Ne jamais mettre d'identifiants MELCloud, mot de passe, jeton ou clé API dans ce dépôt.
- La communication MELCloud devra passer par un backend séparé.
- Commencer en lecture seule et vérifier les données réelles avant d'ajouter des commandes.

## Publication GitHub Pages
Dans le dépôt GitHub : **Settings → Pages**.
Sous **Build and deployment**, choisir **Deploy from a branch**, branche **main**, dossier **/(root)**, puis **Save**.
