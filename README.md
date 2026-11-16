# Hanabi Beat

Jeu de rythme tactile pour téléphone, dans le genre « cercles à toucher en rythme » : on touche chaque cercle quand l'anneau se referme dessus, et on suit la bille sur les rubans.

- 10 cartes, de Débutant (★1,2) à Extrême (★6,8)
- Musiques synthétisées par le jeu (aucun fichier audio), décors de style anime dessinés par le code
- Score, combo, précision, rangs (SS à D), jauge de vie, records enregistrés sur l'appareil
- Réglages : décalage audio, son des touches, mode sans échec, démo automatique

## Jouer

Tout tient dans `index.html`, sans dépendance ni étape de build. Ouvre le fichier dans un navigateur mobile, ou sers le dossier :

```
python3 -m http.server 8000
```

puis ouvre `http://<adresse-du-pc>:8000` sur le téléphone. Le dépôt peut aussi être publié tel quel avec GitHub Pages.

Sur iPhone, le son ne sort pas si l'interrupteur « silencieux » est activé.
